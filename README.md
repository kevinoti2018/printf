PROJECT NAME: PRINTF
GROUP MEMBERS: KEVIN OTIENO & SILVIA WANJIRA
ABOUT PRINTF:
printf is a function in c that is used to print text
and data on the console of a file

SYNTAX: int printf(const char *Format ...)
	First argument is a string that specifies format of output
	ellipsis indicates that the function can take more than one argument
	depending on the number of format specifiers
the format specifiers in c include:
%d - integer
%f - floating-point number
%c - character
%s - string
%p - pointer
%x - hexadecimal integer

RETURN VALUE: printf returns num of chars printed
or negative value of error occurred

SAMPLE PRINTF FUNCTION:
#include <stdio.h>

int main() {
    int x = 42;
    float y = 3.1415;
    char c = 'A';
    char s[] = "Hello, World!";

    printf("x = %d\n", x);
    printf("y = %f\n", y);
    printf("c = %c\n", c);
    printf("s = %s\n", s);

    return 0;
}
OUTPUT OF THE PROGRAM:
x = 42
y = 3.141500
c = A
s = Hello, World!

