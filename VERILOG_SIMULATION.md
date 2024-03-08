
# FUNCTIONAL SIMULATION
**For Ubuntu**

- **To clone the repository and download the netlist files for simulation, enter the following commands in your terminal.**
- `

 Open your terminal and type the following to install iverilog and GTKWave
 ```
 $ git clone https://github.com/Rohansom2003/Rohan
 $   sudo apt get update
 $   sudo apt get install iverilog gtkwave
 $ cd Documents
 $ cd hello
```
 ![rohan1](https://github.com/Rohansom2003/Rohan/assets/160768851/8a883b9f-f0d1-45af-90ab-736122acd911)




- **To simulate and run the Verilog code, enter the following commands in your terminal.**

```
$ iverilog -o hello hello.v hello_tb.v
$ ./hello
```
![rohan2](https://github.com/Rohansom2003/Rohan/assets/160768851/d2f0fa04-cf7f-487e-b951-8dac33fcd2bd)




- **To see the output waveform in gtkwave, enter the following commands in your terminal.**

`$ gtkwave hello.vcd`



  Full 5-stage instruction pipeline and pc-increment description Waveform
  
![rohan3](https://github.com/Rohansom2003/Rohan/assets/160768851/ab8eb91c-45bd-48bc-b1c4-98576642a685)

![rohan4](https://github.com/Rohansom2003/Rohan/assets/160768851/b5eeb5f7-8b41-4ced-80a9-b0fa7a257071)

![rohan5](https://github.com/Rohansom2003/Rohan/assets/160768851/8c3a1b36-46ed-43c2-a5ec-20e1d385edc0)



