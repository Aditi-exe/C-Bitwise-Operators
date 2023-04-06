# Bitwise Operators and their Operations in C

In C, bitwise operators are operators that are used to perform operations on individual bits of integers. They manipulate the bits of integers at the binary level, providing low-level bit-level manipulation capabilities. 

There are six bitwise operators in C:

- **Bitwise AND (&):** This operator compares each bit of the first operand with the corresponding bit of the second operand. If both bits are 1, the result will be 1; otherwise, the result will be 0.

- **Bitwise OR (|):** This operator compares each bit of the first operand with the corresponding bit of the second operand. If either of the bits is 1, the result will be 1; otherwise, the result will be 0.

- **Bitwise XOR (^):** This operator compares each bit of the first operand with the corresponding bit of the second operand. If the bits are different (one is 0 and the other is 1), the result will be 1; otherwise, the result will be 0.

- **Bitwise NOT (~):** This operator is a unary operator and it inverts the bits of its operand. It changes 1s to 0s and 0s to 1s.

- **Left shift (<<):** This operator shifts the bits of the left operand to the left by a specified number of positions. The vacant positions on the right are filled with zeros.

- **Right shift (>>):** This operator shifts the bits of the left operand to the right by a specified number of positions. The vacant positions on the left are filled with zeros (for unsigned integers) or with the sign bit (for signed integers).

Bitwise Operators:

![Bitwise Operators](https://examradar.com/wp-content/uploads/2016/10/Bitwise-operators.png)

Bitwise operators can be used to perform various operations such as setting or clearing individual bits, checking the status of specific bits, or performing bit-level manipulations in C programming. They are commonly used in low-level programming, embedded systems, and device drivers.

The program in this repository demonstrates the usage of bitwise operators to perform operations such as converting an integer to its binary equivalent, counting the number of 1s in a number, checking if a number is a power of two or not, among others.
