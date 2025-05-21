# EXPERIMENT--01-ALP-FOR-8086
Name : AYISHA RINSI K
Roll no :212223040022
Date of experiment : 21-05-2025





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
MOV AL,21H;
MOV BL,30H;
ADD AL,BL;
RET

```

## Output 

![b217615fd2c34dd98a60242589c67a48](https://github.com/user-attachments/assets/e73fbcd2-9f8a-4ae0-85ea-546d3ac36c8f)


## Subtraction   of 8 bit numbers  ALP 
 ```
MOV AL,21H;
MOV BL,30H;
SUB AL,BL;
RET
```

## Output
![b58a6ee6a9394db8a13b8b010bb25ac9](https://github.com/user-attachments/assets/5a4d9893-34bf-49ae-b6e3-b853deb141d1)

## Multiplication alp 
```
MOV AL,21H;
MOV BL,30H;
MUL AL;
RET
```
 ## Output 

![1d349248ce224894b0ab83f9985f373b](https://github.com/user-attachments/assets/5f3a2849-dd32-4162-99e6-941dac1c65c2)


## Division alp 
```
MOV AL,21H;
MOV BL,30H;
DIV AL;
RET
```
## Output  
![4ce472e07e82494d88e525037164fc82](https://github.com/user-attachments/assets/f44ca770-321c-4ae1-9a8b-ce1f3829d23a)


## AND alp
```
MOV AL,21H;
MOV BL,30H;
AND AL,BL;
RET
```
## Output
![and](https://github.com/user-attachments/assets/f79247c9-3781-44ff-a486-8cc2176fdf94)


## OR alp
```
MOV AL,21H;
MOV BL,30H;
OR AL,BL;
RET
```
## Output
![or](https://github.com/user-attachments/assets/17418480-3a30-4f6e-9208-4e8669de1c20)



## NOT alp
```
mov ax,6355h;
mov bx,1233h;
not ax;
ret
```
## Output
![image](https://github.com/user-attachments/assets/de244283-10e3-4d83-a427-2eaa91975ee1)

## XOR alp
```
MOV AL,21H;
MOV BL,30H;
XOR AL,BL;
RET
```
## Output
![xor](https://github.com/user-attachments/assets/0f7f13d3-016e-4150-bf4f-331d91d581a2)



## Result :
 Thus, ALP for fundamental arithmetic and logical operations are executed successfully








