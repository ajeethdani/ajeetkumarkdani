**Execution of the Task 4**


**Use the following instructions to get the gtkwave window**


ls - to check the contents of the folder


iverilog ajeet.v ajeet_tb.v - to simulate the verilog code and to check the errors


./a.out - to get the output and make vcd file to be ready open


![WhatsApp Image 2024-03-20 at 4 14 58 PM](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/4ab702a6-429c-43ac-9710-fa164cc4393f)




**after running the command
gtkwave ajeet.vcd**



![WhatsApp Image 2024-03-20 at 4 17 29 PM](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/cba16b8a-710b-42bc-859c-16a9e2e82e0d)



**Before moving to the execution of the instructions let us understand few parts of a verilog code**

**-the code has been written in a systematic way and broken down into different parts**

1. Instruction Fetch Stage
   
 
![Screenshot 2024-03-20 161957](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/4207e62c-8e17-448e-83d1-f6610d4b81dc)

2. Instruction Decode Stage

  ![Screenshot 2024-03-20 162051](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/80f9a3b7-2e6b-46bb-a285-b0d779b30b19)



3. Instructions Hardcoded

![Screenshot 2024-03-20 162203](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/18c150f0-756a-4c30-b850-3fa5f9d101e4)



**Lets move on to the execution Stage with Waveforms obtained for running the gtkwave ajeet.vcd**


1. When instantiated module is selected we get all the registers and wires as shown in the below figure

![WhatsApp Image 2024-03-20 at 4 23 12 PM](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/80b939ef-ae09-42ca-b2a8-cab741534af2)



2. Upon adding few signals the waves can be see as shown in the below figure

![WhatsApp Image 2024-03-20 at 4 27 02 PM](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/a94be91a-e264-4baa-85eb-5806f302de86)




**Output showing the ADD Operation**


![WhatsApp Image 2024-03-20 at 4 30 02 PM](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/15e40150-f6aa-4eaa-acc9-bae5b3edd18e)


**Output showing the SUB Operation**

![WhatsApp Image 2024-03-20 at 4 32 16 PM](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/2eca97bb-771d-4bc9-ad2a-d7bdbe0914d9)


**Output showing the AND Operation**

![WhatsApp Image 2024-03-20 at 4 36 05 PM](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/93598fe0-75e6-4e81-94f8-df1f651d43b5)


**Output showing the OR Operation**

![WhatsApp Image 2024-03-20 at 4 37 40 PM](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/30e8a69c-ae7c-487e-aea6-d8c3bf386db5)



**Output showing the XOR Operation**

![WhatsApp Image 2024-03-20 at 4 39 05 PM](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/e21ef08f-453f-4b99-8895-3ebed15a3007)
