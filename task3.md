**By Referring to C-based Lab videos and RISC-V-based lab videos**

**Snapshots of the compiled C code and RISC-V**

**Step 1: check whether the leafpad is installed in ur machine by using the commands
leafpad sum1ton.c& (sum1ton.c is the file name)
If the leafpad editor is opened without any errors then type the C code.**
****If the leafpad is not installed in ur machine then install by using the following command**

**sudo snap install leafpad****


****Step 2: Writing the C code in the leafpad editor** using the following command

**leafpad sum1ton.c&**

![WhatsApp Image 2024-02-27 at 10 58 21 AM (1)](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/21229fef-81a7-4fd6-af08-85449990a4b8)

**Step 3: After writing the C code save the editor by Ctrl+s**

![WhatsApp Image 2024-02-27 at 10 58 21 AM (2)](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/a9003904-6d39-479c-a587-dfe039a9d9b5)


**Step 4: Check for the errors by using the following command(compilation step)**

**gcc sum1ton.c**

**Step 5: Check the output by using the command**

**./a.out**

![WhatsApp Image 2024-02-27 at 10 58 21 AM (3)](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/a22279f0-6b21-436f-8793-0d69fdaf8e54)

**The results will be displayed as** 

**Sum of numbers from 1 to 50 is 12**


********************************************************RISCV Compilation and Execution*****************************************************

**Step 1: View the C Code in the editor window using the following command**

**cat sum1ton.c**
![WhatsApp Image 2024-02-27 at 11 51 41 AM](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/8cfda518-af70-4453-8c98-78517e8dd6d9)


**Step 2: Compile the code in riscv using the following command**

**riscv64-unknown-elf-gcc -O1 -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c**
![WhatsApp Image 2024-02-27 at 11 51 41 AM](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/d06ea136-fbcf-49d0-955e-4284891ccb4d)


**Step 3: The ls ltr command in Linux is used to list the contents of the current directory in long format, sorted by last modified time in reverse order.**

**use the command**

**ls -ltr sum1ton.c**

![view the directory contents](https://github.com/Abdulbitm/Abdul/assets/160620896/c7dd20be-b896-4d19-af98-077590a23b14)


![long directory content](https://github.com/Abdulbitm/Abdul/assets/160620896/3e2e473a-9f55-4bec-8ed3-4bd2732efbee)

**Search for the Main and check the instructions of the C code execution. It has 15 instructions in the C execution**

![checking instructions_in_main_C_Code_15_instructions](https://github.com/Abdulbitm/Abdul/assets/160620896/8d7d1502-a997-403d-a2cc-fcd459962a43)

![checking instructions_in_main_C_Code_15_instructions_highlighted](https://github.com/Abdulbitm/Abdul/assets/160620896/0a07ba3e-4a3d-41a7-a158-3ef976ce0292)


**Step 4:**

**riscv64-unknown-elf-gcc -Ofast -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c**

![12 instructions with Ofast](https://github.com/Abdulbitm/Abdul/assets/160620896/f2ebdc19-c3a6-494d-a25d-6d71c2811440)



![12 instructions with Ofast_1](https://github.com/Abdulbitm/Abdul/assets/160620896/4904feb4-c3ab-4337-976c-9a94bacbf85a)






