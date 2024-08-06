# EXperiment-4
## Aim:
The aim of this program is to demonstrate the bitwise operations and shifts in C++ using predefined integer values for variables a and b.

## Theory:
In the provided C++ program: Variables Initialization: a is initialized to 5 (int a = 5;). b is initialized to 3 (int b = 3;).

Bitwise Operations: AND (a & b): Performs a bitwise AND operation between a and b. Result is 1 (binary 101 & 011). OR (a | b): Performs a bitwise OR operation between a and b. Result is 7 (binary 101 | 011). XOR (a ^ b): Performs a bitwise XOR operation between a and b. Result is 6 (binary 101 ^ 011). NOT (~a): Performs a bitwise NOT operation on a. Result is -6 (bitwise complement of 5). LEFT SHIFT (a << b): Shifts bits of a left by b positions. Result is 40 (binary 101 << 3). RIGHT SHIFT (a >> b): Shifts bits of a right by b positions. Result is 0 (binary 101 >> 3).

## Code
~~~
/*AARYA JIRWANKAR
23070123161
EXPREIMENT 4 - BITWISE OPERATORS (AND ,OR, NOT, XOR, LEFT SHIFT, RIGHT SHIFT)
*/


#include<iostream>
using namespace std;

int main()
{
    int a = 16; // 16 in binary is 10000
    int b = 14; // 14 in binary is 01110
    int c = a & b;
    int d = a | b;
    int e = a ^ b ;
    int f = ~a;
    cout << "The bitwise and value of 16 and 14 is: "<< c<< endl;
    cout << "The bitwise or value of 16 and 14 is: "<< d<< endl;
    cout << "The bitwsie xor value of 16 and 14 is: "<< e<< endl;
    cout << "The butwise not value of 16 is: "<< f<< endl;
    cout << "Left shifted value of a "<< (a<<1)<< endl;
    cout << "Right shifted value "<< (b>>1)<< endl;
    return 0;

}

/*
OUTPUT OF THE CODE: -
The bitwise and value of 16 and 14 is: 0
The bitwise or value of 16 and 14 is: 30
The bitwsie xor value of 16 and 14 is: 30
The butwise not value of 16 is: -17
Left shifted value of a 32
Right shifted value 7
*/
~~~
## Conclusion:
The program successfully demonstrates the basic bitwise operations (AND, OR, XOR, NOT) and shifts (LEFT_SHIFT, RIGHT_SHIFT) in C++. Each operation's result is printed to the console, showcasing how these operations manipulate the bits of integer values a and b. The output matches the expected values based on binary arithmetic, confirming the correctness of the bitwise operations and shifts implemented in the program.

