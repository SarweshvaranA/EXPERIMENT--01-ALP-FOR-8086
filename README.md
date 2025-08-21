## SARWESHVARAN A
## 212223230198
## 18/08/2025
# EXPERIMENT--01-ALP-FOR-8086






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







## Programs for arithmetic  operations:

## Addition  of 8 bit ALP:

```
org 100h

mov ax,1234h
mov bx,4321h
add ax,bx

ret
```



## Output :

<img width="1173" height="806" alt="Screenshot 2025-08-18 142145" src="https://github.com/user-attachments/assets/562de3b3-dfb7-4a13-bc8e-1d49fa5c87e6" />

 
## Subtraction   of 8 bit numbers  ALP :
```
org 100h
mov ax, 2A34h
sub ax, [0200h]   ;
ret
```
 
## Output:




<img width="1156" height="795" alt="Screenshot 2025-08-21 133149" src="https://github.com/user-attachments/assets/824f507d-a9f2-4c3a-a01c-470fd10af800" />


## Multiplication alp :
```
org 100h   

num DW 2521h
mov ax,5d89h
mul num 


ret


```
 ## Output :
 
<img width="1152" height="774" alt="Screenshot 2025-08-21 134502" src="https://github.com/user-attachments/assets/2e69c8a9-c1b6-4e1d-bd8e-af8850b687ca" />

 
 


## Division alp:
```
org 100h

num dw 5d89h
mov bx, OFFSET num
mov ax,8f09h
div word ptr[bx]

ret

```



## Output :
<img width="1151" height="769" alt="image" src="https://github.com/user-attachments/assets/c70af26a-b921-45dd-8c7d-cfa513b5ef8f" />


## Programs for logical  operations:

## AND:
```
org 100h

mov ax,1234h
mov bx,4321h
and ax,bx

ret
```
## Output:

<img width="1142" height="765" alt="image" src="https://github.com/user-attachments/assets/9724804f-0c35-4153-a027-29155bdb86b5" />



## OR:
```
org 100h

mov ax,1234h
mov bx,4321h
and ax,bx

ret

```

<img width="1152" height="773" alt="image" src="https://github.com/user-attachments/assets/20d7f8ee-3639-4108-a54a-594e9fd301a4" />


## NOT:
```
org 100h

mov ax,5d89h
mov bx,2521h
not ax,bx

ret
```
## Output:


<img width="1151" height="770" alt="image" src="https://github.com/user-attachments/assets/0277034d-2b81-4515-ab49-d11a7d434c13" />

## XOR:
```
org 100h

mov ax,5d89h 
mov bx,5432h
xor ax,bx

ret

```

## Output:

<img width="1154" height="776" alt="image" src="https://github.com/user-attachments/assets/876c1391-70e1-402c-8af6-5a3d91e4e617" />



## Result :

Thus the execution of ALP on fundamental arithmetic and logical operations is successfully completed.

 








