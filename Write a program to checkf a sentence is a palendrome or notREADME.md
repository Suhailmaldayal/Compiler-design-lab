/ Write a program that checks if a sentence is a palindrome or not.

// This program ignores the white spaces in the sentence. For example, "ab ba" is a palindrome although it is not a palindrome if we consider the white spaces.

#include <stdio.h> #include <string.h>

// Function to remove all spaces from a given string void removeSpaces (char *str) // *str is a pointer to the first character of the string

(

int 10, j = 0; while (str[i])

if (str[i] != '')

str[j++] = str[i];

1++;

} str[j] = '\0'; // Null-terminate the string

}

int main()

{ char str[100]; printf("Enter a string you want to check: "); gets (str); // Reads the line with spaces

removeSpaces (str); // Remove spaces from the string

int len = strlen(str);

int i = 0; int len // iterating from the start 1; // iterating from the end

int flag 0;

while (i < j)

if (str[i] != str[j])

flag = 1;

break;

1

1++;

ゴーーン

if (flag= 0)

printf("The string is a palindrome\n");

else

printf("The string is not a palindrome\n");
