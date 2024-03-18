ASCII value of a character in C
Here, in this section we will discuss program to find the ASCII value of a character in C. ASCII value can be any integer number between 0 and 127 and consists of character variable instead of the character itself in C programming.

ASCII value of a character in C
While loop in C
Did you know?
 ASCII stands for American Standard Code for Information Interchange
Which is a binary code used by electronic equipment for electronic communications
A total of 128 characters have been assigned values from 0 – 127
Alphabets (  65 – 90  &  97 – 122  )
Digits (  48 – 57  )
Remaining are Special Character (  !, @, #, $, * …..)
Working
User gives an input
Input is stored in a char type variable say val.
val is converted from char to int .
The ASCII value of Character is Obtained
ASCII value of a character
C code
Run
// C Program to identify ASCII Value of a Character
#include <stdio.h>

int main()
{
	char a='5';
	
	
	printf("The ASCII value of %c is %d",a,a);
	
	return 0;
}
Output
The ASCII value of 5 is 53
