# EXPERIMENT--01-ALP-FOR-8086
Name :SANGAVI SURESH

Roll no :212222230130

Date of experiment : 01





## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
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

## Addition 
```
org 100H
mov AH,0A2H;
mov BH,0B3H;
add AH,BH;
HTL
```
## Output  
 ![305803205-38a0497a-0729-47ac-98aa-932ed1cbcb2d](https://github.com/Sangavi-suresh/EXPERIMENT--01-ALP-FOR-8086/assets/118541861/2ff34757-782f-4f3a-a209-4fa7284113d8)

## Subtraction  
```
 org 100H
mov Ax,7024H;
mov Bx,5220H;
sub Ax,Bx;
HTL
```
## Output  

![316785524-7181ec4b-60a3-4572-aa56-058dbb16fc12](https://github.com/Sangavi-suresh/EXPERIMENT--01-ALP-FOR-8086/assets/118541861/c0151e07-b00f-4efc-98bc-66f3ee9be1b4)

## Multiplication
```
org 100H
mov AL,65H;
mov BL,08H;
mul BL;
HLT
```
 ## Output  

![316785367-4ffa4d0e-4c0f-439b-a71d-7ee4f475f035](https://github.com/Sangavi-suresh/EXPERIMENT--01-ALP-FOR-8086/assets/118541861/26af652f-fb1a-440e-8ac4-20607b2458b0)

## Division 
```
org 100H
mov AL,75H;
mov BL,06H;
div BL;
HLT
```
## Output  

![316782591-9bda73c5-c1e7-4e80-a38b-36d63df70090](https://github.com/Sangavi-suresh/EXPERIMENT--01-ALP-FOR-8086/assets/118541861/54922c83-623e-4619-a4e4-61776f6e4fa8)


### Program for logical operations

### AND operation
```
org 100h
MOV AH,12H;
MOV BH,45H;
AND AH,BH
HLT
```

### AND OUTPUT:

![316792879-5b83fc37-c545-4915-8fdc-5086cb88acf7](https://github.com/Sangavi-suresh/EXPERIMENT--01-ALP-FOR-8086/assets/118541861/09412a56-6bde-4e05-be14-095aa3a84d3a)

### OR operation
```
org 100h
MOV AH,56H
MOV BH,67H
OR AH,BH
HLT
```
### OR OUTPUT

![316794562-7099ef0d-e23c-42ee-b566-37cf2d62aea9](https://github.com/Sangavi-suresh/EXPERIMENT--01-ALP-FOR-8086/assets/118541861/50de1470-53ca-42b2-89a5-3d1bd4c3b6d6)

### NOT operation
```
org 100h
MOV AX,1234H
NOT AX
HLT
```
### NOT OUTPUT

![316794641-66eab738-805c-458e-856c-41f2671a9028](https://github.com/Sangavi-suresh/EXPERIMENT--01-ALP-FOR-8086/assets/118541861/c001e067-3175-4372-a4f6-de5dd2b239df)

### XOR operation
```
org 100h
MOV AL,99H
MOV BL,88H
XOR AL,BL
HLT
```
### XOR OUTPUT

![316796398-6d7a3d26-83d5-454f-8df5-e8acfef53b56](https://github.com/Sangavi-suresh/EXPERIMENT--01-ALP-FOR-8086/assets/118541861/162c7ee6-26a9-48b5-bd1d-1cc8ec2aab0e)

## Result :
 
Thus, a program is executed on ALP for the fundamental arithmetic and logical operations.







