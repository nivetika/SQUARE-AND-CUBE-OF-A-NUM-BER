# SQUARE AND CUBE OF A NUMBER
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```
ORG 00H
MOV R0,#50H
MOV A,@R0
MOV B,@R0
MUL AB
INC R0
MOV @R0,A
END
```

## OUTPUT

<img width="365" height="243" alt="image" src="https://github.com/user-attachments/assets/58bd4ce3-e04c-4c6e-9003-f7601cfd81c6" />
<img width="567" height="201" alt="Screenshot 2025-09-27 124526" src="https://github.com/user-attachments/assets/7f4cd8b9-9744-400e-ab5c-b9e830ff1361" />


## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```
ORG 00H
MOV R0,#50H
MOV A,@R0
MOV B,A
MUL AB
MOV B,@R0
MUL AB
INC R0
MOV @R0,A
INC R0
MOV @R0,B
END
```


## OUTPUT

<img width="322" height="336" alt="image" src="https://github.com/user-attachments/assets/c8e704cd-c2cd-46b1-ac54-a9b0bbb0ec76" />
<img width="743" height="336" alt="image" src="https://github.com/user-attachments/assets/a3af78d6-c8b4-4ef4-9981-ae0f8baeca94" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
