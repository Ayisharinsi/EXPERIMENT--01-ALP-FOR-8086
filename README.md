# EXPERIMENT--01-ALP-FOR-8086
Name : AYISHA RINSI K
Roll no :212223040022
Date of experiment :





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

## Addition  of 8 bit ALP 
```
org 100h
mov ax,3244h;
mov bx,3422h;
add ax,bx;
mov [8975h],ax; 

ret
```

## Output 
![image](https://github.com/user-attachments/assets/35173338-fb72-46f4-b5e7-ef812a312d07)


## Subtraction   of 8 bit numbers  ALP 
 ```
org 100h
mov ax,6544h;
mov bx,8765h;
sub ax,bx;
mov [8765h],al; 

ret
```

## Output
![image](https://github.com/user-attachments/assets/47450a52-ab27-4d4d-8b43-efb57dc90a1c)


## Multiplication alp 
```
org 100h
mov ax,3244h;
mov bx,1222h;
mul ax;
mov [8754h],al; 

ret
```
 ## Output 
 ![image](https://github.com/user-attachments/assets/338f9f26-4d23-4702-b23e-c3a8cb13af9e)


## Division alp 
```
org 100h
mov ax,2233h;
mov bx,2766h;
div ax;
mov [7655h],ax; 

ret
```
## Output  
![image](https://github.com/user-attachments/assets/c582aab0-d452-493b-8ddb-4ae9ec33e772)

## AND alp
```
org 100h
mov ax,1232h;
mov bx,8722h;
and ax,bx;
mov [6755h],bx; 

ret
```
## Output
![image](https://github.com/user-attachments/assets/1cebadc0-9700-43fa-b856-4ffc869d966d)

## OR alp
```
org 100h
mov ax,3244h;
mov bx,0199h;
xor ax,bx;
mov [3211h],ax; 

ret
```
## Output
![image](https://github.com/user-attachments/assets/89cf4aa8-13b5-4d98-aba8-b6e83fd54dcc)

## NOT alp
```
org 100h
mov ax,6355h;
mov bx,1233h;
not ax;
mov [7655h],ax; 

ret
```
## Output
![image](https://github.com/user-attachments/assets/de244283-10e3-4d83-a427-2eaa91975ee1)

## XOR alp
```
org 100h
mov ax,3244h;
mov bx,0199h;
xor ax,bx;
mov [3211h],ax; 

ret
```
## Output
![image](https://github.com/user-attachments/assets/b13690b4-3e55-4cf3-b3be-e7b5b1953e2e)


## Result :
 Thus, ALP for fundamental arithmetic and logical operations are executed successfully








