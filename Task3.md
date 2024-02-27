**By Referring to C-based Lab videos and RISC-V-based lab videos**

**Snapshots of the compiled C code and RISC-V**

**Step 1: check whether the leafpad is installed in ur machine by using the commands
leafpad sum1ton.c& (sum1ton.c is the file name)
If the leafpad editor is opened without any errors then type the C code.**
****If the leafpad is not installed in ur machine then install by using the following command**

**sudo snap install leafpad****


****Step 2: Writing the C code in the leafpad editor** using the following command

**leafpad sum1ton.c&**
![task3img1](https://github.com/Rohansom2003/Rohan/assets/160768851/21d422eb-468b-485a-b3aa-86e6cabb7300)



**Step 3: After writing the C code save the editor by Ctrl+s**

![task3img2](https://github.com/Rohansom2003/Rohan/assets/160768851/5112f2e8-1d9d-4a30-981e-ff2b35f98567)



**Step 4: Check for the errors by using the following command(compilation step)**

**gcc sum1ton.c**

**Step 5: Check the output by using the command**

**./a.out**

![task3img3](https://github.com/Rohansom2003/Rohan/assets/160768851/1195ae30-c793-47b7-9390-5102fb7a89ed)


**The results will be displayed as** 

**Sum of numbers from 1 to 500 is 125250**


********************************************************RISCV Compilation and Execution*****************************************************

**Step 1: View the C Code in the editor window using the following command**

**cat sum1ton.c**
![task3img4](https://github.com/Rohansom2003/Rohan/assets/160768851/1bf5b31a-2a16-4d3e-b557-9bc81ed5446f)


**Step 2: Compile the code in riscv using the following command**

**riscv64-unknown-elf-gcc -O1 -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c**

**Step 3: The ls ltr command in Linux is used to list the contents of the current directory in long format, sorted by last modified time in reverse order.**

**use the command**

**ls -ltr sum1ton.c**

![task3img5](https://github.com/Rohansom2003/Rohan/assets/160768851/84523890-aa27-4634-bb89-f1023a906dad)


**Search for the Main and check the instructions of the C code execution. It has 15 instructions in the C execution**


**Step 4:**

**riscv64-unknown-elf-gcc -Ofast -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c**

![task3img6](https://github.com/Rohansom2003/Rohan/assets/160768851/4d3d98ea-9966-47ae-a831-67186282773e)





