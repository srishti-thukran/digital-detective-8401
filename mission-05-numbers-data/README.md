## TASK-5.1 Convert numbers by hand

| Questions | Answer |
|-----------|--------|
| Convert decimal 13 to binary | 1101 |
| Convert decimal 25 to binary | 11001 |
| Convert binary 1010 to decimal | 10 |
| Convert binary 1101 to decimal | 13 | 
| Convert hexadecimal A to decimal | 10 |
| Convert Hexadecimal 1F to decimal | 31 |
| Convert binary 1111 to hexadecimal | F |

## TASK-5.4 How is text stored?

----> Find the ASCII decimal codes for the uppercase letter A and lowercase letter a
A-65
a-97

----> Why a computer needs an encoding standard to store text
A computer needs an encoding standard to store text because computers understand only binary data (0s and 1s), not letters, numbers, or symbols directly.An encoding standard assigns a unique numerical value to each character so that computers can convert text into binary and store or transmit it.
Without a common encoding standard, different computers might interpret the same binary data as different characters, causing incorrect text to appear.

----> one example of a character that is not part of basic ASCII
the euro symbol 

-------------------------------------------------------------------------------------------------------
 
 ## 1. Python functions used
input() – Takes input from the user.
int() – Converts input into an integer.
bin() – Converts a decimal integer into binary.
hex() – Converts a decimal integer into hexadecimal.
print() – Displays output.
ord() – Returns the ASCII/Unicode value of a character.
 
## 2. How the converter works ?
The program asks the user to enter a decimal number. It converts the input into an integer using int(). The bin() function converts the number into binary, while hex() converts it into hexadecimal. Finally, both results are displayed using print().

## 3. What I understood ?
Computers store information using binary digits (0s and 1s).
Decimal, binary and hexadecimal are different number systems.
Python provides built-in functions for number conversion.
ASCII assigns numerical values to characters.
Encoding standards help computers represent and exchange text consistently.
Basic ASCII does not include characters such as the Euro symbol .



