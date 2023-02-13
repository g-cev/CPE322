# Lab 1: Half Adder and 4-to-1 Multiplexer

## Half Adder

### Procedure

Below are the terminal commands I used to compile and execute the Half Adder lab's VHDL code:

```
$ cd C:/eda/half adder
$ ghdl -a ha.vhdl
$ ghdl -a ha_tb.vhdl
$ ghdl -e ha_tb
$ ghdl -r ha_tb --vcd=ha.vcd
$ gtkwave ha.vcd
```


### Results

![Half Adder Results](https://user-images.githubusercontent.com/87401577/215926259-7f03ef80-3ac4-4aab-9c91-fbfee6398bc0.PNG)

## 4-to-1 Multiplexer

### Procedure
Below are the terminal commands I used to compile and execute the 4-to-1 Multiplexer lab's VHDL code:

```
$ cd C:/eda/4to1MUX
$ ghdl -a mux.vhdl
$ ghdl -a mux_tb.vhdl
$ ghdl -e mux_tb
$ ghdl -r mux_tb --vcd=mux.vcd
$ gtkwave mux.vcd
```

### Results
![results](https://user-images.githubusercontent.com/87401577/215930181-c3c69c84-f88f-4d8c-bd24-431439dc2a78.PNG)

## What I Learned

When installing GTKWave and GHDL onto my laptop, I did not understand the reasoning behind editing the system PATH to include their directories. I later realized that doing so allows me to execute a program and commands without having to go to the file location of the executable.

It is important to note that it is easier to enter the directories of GHDL and GTKWave's bin folder into the system PATH. This should be done to avoid having to type ".exe" when entering a command into the terminal, since both executables reside in their respective bin folders. 

I also learned that in order to run code files through these programs, it is best to keep the code in its own folder so the terminal can find it without making the user change directories.

![code setup](https://user-images.githubusercontent.com/87401577/215926530-f134a2be-fbd2-4a7f-9890-cfabdad36c5e.PNG)

