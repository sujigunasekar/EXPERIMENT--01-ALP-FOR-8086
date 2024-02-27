# EXPERIMENT--01-ALP-FOR-8086
Name : SUJI.G
Roll no :212222230152
Date of experiment :27.2.23
## Aim: 
To Write and execute ALP on fundamental arithmetic and logical operations
## Components required:
8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
mov al,34h
mov bl,84h
add al,bl
hlt
```
## Output  
![308096275-c5ace418-748a-4176-91ad-2eae46a83a06](https://github.com/sujigunasekar/EXPERIMENT--01-ALP-FOR-8086/assets/119559822/487b1f5b-47ae-470c-bc84-73a208e77657)

## Subtraction   of 8 bit numbers  ALP 
```
mov al,56h
mov bl,45
sub al,bl
hlt
```
## Output  
![308095220-acfd52e2-b210-4bb1-b578-fed6914347a5](https://github.com/sujigunasekar/EXPERIMENT--01-ALP-FOR-8086/assets/119559822/00b16a40-0e3c-4eeb-aa1c-b8ea09dee4b5)

## Multiplication of 8 bit ALP 
```
mov al,45
mov bl,56
mul bl
hlt
```
## Output  
![308095321-8458cd7e-7e0a-40c8-b833-ee45a6c57d4f](https://github.com/sujigunasekar/EXPERIMENT--01-ALP-FOR-8086/assets/119559822/e29a82f1-cf99-4019-8358-33d9b9549b7b)



## Division of 8 bit ALP 
```
mov al,45h
mov bl,56h
div bl
hlt
```
## Output  
![308095384-ddb7bc2c-2bff-4a9a-8c98-c39149b66c02](https://github.com/sujigunasekar/EXPERIMENT--01-ALP-FOR-8086/assets/119559822/7fd97387-900d-49ad-8ff3-9e7236355521)


## Result :

 
Thus, a program is executed on ALP for the fundamental arithmetic and logical operations.







