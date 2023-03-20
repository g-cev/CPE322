# Lab 7: ThingSpeak and Google Sheets

## Procedure

First, I signed up and logged into MathWorks ThingSpeak:

![thing speak](../lab7/assets/thingspeak1.PNG)

Then, I ran thingspeak_cpu_loop.py or thinkspeak_feed.py in a demo folder and copied thingspeak_feed.py and thingspeak_cpu_loop.py into it:

![new demo folder](../lab7/assets/newDemoFolder.PNG)
![copied folders into demo](../lab7/assets/demo2.PNG)

After running the programs and including the API key generated in ThingSpeak, I was able to see the result channels below.
It was interesting to see the spike in the CPU chart since I had the program running while closing my laptop and moving somewhere else:

(API KEY screenshots was edited out)

![channel results](../lab7/assets/API3.PNG)

Next, I installed gspread and oauth2client:

![GSpread](../lab7/assets/installGspread.PNG)

![OAuth2Client](../lab7/assets/installOath2client.PNG)

After logging into the Google Cloud Platform Identity and Access Management, I created a project, "cpudata".
Then I enabled both Drive API and Sheets API and created/downloaded a service account JSON key file:

![create account JSON](../lab7/assets/createAPIJSON.PNG)

Finally, I started a new Google sheet cpudata, shared it with the client email in the JSON file and edited the necessary rows in cpu_worksheet.py:

![JSON file screenshot](../lab7/assets/jsonSS.PNG)

![edited file](../lab7/assets/edited_WSpy.PNG)

Here are the results from running cpu_spreadsheet.py with the JSON key file in a demo folder:

![final results](../lab7/assets/results.PNG)
