
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
ORG 0000H
 MOV A, P0
 MOV R0, A
 MOV B, R0
 MUL AB
 MOV P2, A
 SJMP $
 END
```
## OUTPUT
![WhatsApp Image 2025-11-11 at 11 29 03_fd2fc112](https://github.com/user-attachments/assets/dda3494c-de4b-40cb-88ca-fc746a7bc208)


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
 ORG 0000H
 MOV A, P0
 MOV B, A
 MUL AB
 MOV R0, P0
 MOV B, R0
 MUL AB
 MOV P2, A
 SJMP $
 END
```
## OUTPUT
![WhatsApp Image 2025-11-11 at 11 29 35_eed0bad7](https://github.com/user-attachments/assets/e20c620a-128f-4913-b661-f8419064c55c)

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
