#More pointers, clusters and strings.

#Errands

0. strcat

Compose a capability that links two strings.

Model: burn *_strcat(char *dest, scorch *src);
This capability adds the src string to the dest string, overwriting the ending invalid byte (\0) toward the finish of dest, and afterward adds an ending invalid byte
Returns a pointer to the subsequent string dest
FYI: The standard library gives a comparative capability: strcat. Run man strcat to find out more.

1. strncat

Compose a capability that connects two strings.

Model: scorch *_strncat(char *dest, roast *src, int n);
The _strncat capability is like the _strcat capability, then again, actually
it will use all things considered n bytes from src; and
src needn't bother with to be invalid ended in the event that it contains n or more bytes
Return a pointer to the subsequent string dest
FYI: The standard library gives a comparative capability: strncat. Run man strncat to find out more.

2. strncpy

Compose a capability that duplicates a string.

Model: burn *_strncpy(char *dest, scorch *src, int n);
Your capability ought to work precisely like strncpy
FYI: The standard library gives a comparable capability: strncpy. Run man strncpy to find out more.

3. strcmp

Compose a capability that looks at two strings.

Model: int _strcmp(char *s1, burn *s2);
Your capability ought to work precisely like strcmp
FYI: The standard library gives a comparative capability: strcmp. Run man strcmp to find out more.

4. I'm a sort of jumpy in switch. I suspect individuals of plotting to satisfy me

Compose a capability that switches the substance of a variety of numbers.

Model: void reverse_array(int *a, int n);
Where n is the quantity of components of the exhibit

5. Continuously gaze upward

Compose a capability that changes generally lowercase letters of a string to capitalized.

Model: burn *string_toupper(char *);

6. Anticipate the best. Plan for terrible. Exploit what comes

Compose a capability that underwrites all expressions of a string.

Model: roast *cap_string(char *);
Separators of words: space, arrangement, new line, ,, ;, ., !, ?, ", (, ), {, and }

7. Mozart made his music not for the world class, but rather for everyone

Compose a capability that encodes a string into 1337.

Letters an and An ought to be supplanted by 4
Letters e and E ought to be supplanted by 3
Letters o and O ought to be supplanted by 0
Letters t and T ought to be supplanted by 7
Letters l and L ought to be supplanted by 1
Model: roast *leet(char *);
You can utilize one if in your code
You can involve two circles in your code
You are not permitted to utilize switch
You are not permitted to utilize any ternary activity

8. rot13

Compose a capability that encodes a string utilizing rot13.

Model: scorch *rot13(char *);
You can utilize if articulation once in your code
You can involve two circles in your code
You are not permitted to utilize switch
You are not permitted to utilize any ternary activity

9. Numbers have life; they're not only images on paper

Compose a capability that prints a whole number.

Model: void print_number(int n);
You can utilize _putchar capability to print
You are not permitted to utilize long
You are not permitted to utilize exhibits or pointers
You are not permitted to hard-code unique qualities

10. A fantasy doesn't become reality through enchantment; it takes sweat, assurance and difficult work

Add one line to this code, with the goal that the program prints a[2] = 98, trailed by another line.

You are not permitted to utilize the variable an in your new line of code
You are not permitted to change the variable p
You can keep in touch with one explanation
You are not permitted to utilize ,
    You are not permitted to code anything more than the line of anticipated line of code at the normal line
    Your code ought to be composed at line 19, preceding the ;
    Eliminate nothing from the underlying code (not even the remarks)
	furthermore, change nothing yet the line of code you are adding (don't change the spaces to tabs!)
	You are permitted to utilize the standard library

	11. The expansion of weirdness to excellence is the heartfelt person in craftsmanship

	Compose a capability that adds two numbers.

	Model: scorch *infinite_add(char *n1, roast *n2, singe *r, int size_r);
	Where n1 and n2 are the two numbers
	r is the cushion that the capability will use to store the outcome
	size_r is the support size
	The capability returns a pointer to the outcome
	You can expect that you will continuously get positive numbers, or 0
	You can expect that there will be just digits in the strings n1 and n2
	n1 and n2 won't ever be vacant
	In the event that the outcome can not be put away in r the capability should bring 0 back

	12. Commotion is a cushion, more powerful than work spaces or corner walls

	Compose a capability that prints a support.

	Model: void print_buffer(char *b, int size);
	The capability should print the substance of size bytes of the support pointed by b
	The result ought to print 10 bytes for each line
	Each line begins with the place of the main byte of the line in hexadecimal (8 roasts), beginning with 0
	Each line shows the hexadecimal substance (2 burns) of the support, 2 bytes all at once, isolated by a space
	Each line shows the substance of the support. In the event that the byte is a printable person, print the letter, on the off chance that not, print .
	Each line closes with another line \n
	On the off chance that size is 0 or less, the result ought to be another line just \n
	You are permitted to utilize the standard library
	The result ought to seem to be the accompanying model, and designed the very same way
