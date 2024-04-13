# Remainder.c
1. We include the necessary header file stdio.h for input and output operations.
2. In the main function, we declare two integer variables number to store the input number and reverse to store the reversed number.
3. We prompt the user to enter a 3-digit number using printf and read the input using scanf.
4. We check if the input number is a valid 3-digit number by ensuring it falls within the range 100-999.
5. We then reverse the number by repeatedly extracting the last digit of the number using the modulo operator % and adding it to the reverse variable after shifting it one place to the left by multiplying by 10.
6. We update the number by removing the last digit using integer division /.
7. We repeat this process until the original number becomes 0.
8. Finally, we print the reversed number using printf.

To compile and run this program, save it in a file named reverse.c and use a C compiler like GCC:
