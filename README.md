# EXPERIMENT--01-ALP-FOR-8086
## Name : Nishanth R S


## Roll no : 2212224040223






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
Mov AL,74H
MOV BL,69H
ADD AL,BL
HLT
```

## Output  


<img width="1230" height="700" alt="image" src="https://github.com/user-attachments/assets/7f4452f6-1131-45e3-830c-f85c2efc84bc" />

 
## Subtraction   of 8 bit numbers  ALP 

```
Mov AL,74H
MOV BL,69H
SUB AL,BL
HLT
```


 
## Output  

<img width="1215" height="811" alt="image" src="https://github.com/user-attachments/assets/00760c44-39e3-48a5-a6c3-84273b307f53" />



## Multiplication alp 

```
org 100h
Mov AL,74H
MOV BL,69H
MUL BL
HLT
ret
```


 ## Output  


 <img width="1181" height="695" alt="image" src="https://github.com/user-attachments/assets/2b59e8a2-16ab-404a-8e24-54bbbf889f78" />



## Division alp 



```
MOV AL,68H
MOV BL,18H
DIV BL
HLT
```



## Output  



<img width="1076" height="657" alt="image" src="https://github.com/user-attachments/assets/727037ac-42ff-4504-a306-41ad0cac42dd" />


## And of 8 bit numbers ALP



```
MOV AL,33H
MOV BL,44H
AND AL,BL
HLT
```

## Output


<img width="1247" height="734" alt="image" src="https://github.com/user-attachments/assets/99c1e6d9-4a4a-45ca-b90b-e50e416b79b1" />



## OR of 8 bit numbers ALP

```
MOV AL,45H
MOV BL,66H
OR AL,BL
HLT
```

## Output

<img width="1397" height="735" alt="image" src="https://github.com/user-attachments/assets/a602ef80-2236-4885-ac45-c7da5c739809" />


## NOT of 8 bit number ALP

```
MOV AL,65H
NOT AL
HLT
```

## Output

<img width="1188" height="770" alt="image" src="https://github.com/user-attachments/assets/94395a54-8144-445b-b8cf-c52f86ae9393" />



## XOR of 8 bit number ALP


```
MOV AL,66H
MOV BL,77H
XOR AL,BL
HLT
```

## Output


<img width="1177" height="752" alt="image" src="https://github.com/user-attachments/assets/57dcb78a-b599-44ef-87cc-85a1cd6ed9d3" />


## Result :

The execution of ALP on fundamental arithmetic and logical operations is successfully completed.
