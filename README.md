# EX-NO-6-Pseudo-Random-Number
# Reg no: 212224230203
# Name:P.Pramisha
# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```
#include <stdio.h> 
#include <stdlib.h> 
#include <time.h> 
int main() { 
int i, n; 
srand(time(0)); 
printf("Enter how many pseudorandom numbers you want to generate: "); 
scanf("%d", &n); 
printf("Generating %d pseudorandom numbers between 0 and 99:\n", n); 
for (i = 0; i < n; i++) { 
int randomNumber = rand() % 100; 
printf("%d ", randomNumber); 
} 
printf("\n"); 
return 0; 
}
```
# OUTPUT:
<img width="897" height="914" alt="Screenshot 2026-02-11 160650" src="https://github.com/user-attachments/assets/e591c935-fb54-456a-b8e1-7524e9852bad" />

# RESULT:
Implementation of Pseudorandom Number Generation Using Standard library is successful.
