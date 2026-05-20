# Square-Cube-of-a-number-using-8051
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
MOV RO, #50H
MOV A, @Re
MOV B, @RE
MUL AB
INC RØ
MOV @RO,A
END
```

## OUTPUT

<img width="1452" height="417" alt="image" src="https://github.com/user-attachments/assets/02229d02-9436-4c5a-a910-e9d56aa36d74" />


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
MOV A, P0
MOV B, A
MUL AB
MOV R0, A
MOV A, R0
MOV B, P0
MUL AB
MOV P2, A
END
```
## OUTPUT

<img width="937" height="666" alt="image" src="https://github.com/user-attachments/assets/253c094c-0bdd-4354-ad03-a27f9f3ad67d" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.







