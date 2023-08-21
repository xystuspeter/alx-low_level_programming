C - Pointers, exhibits and strings

#Errands

0. 98 Battery st.

Compose a capability that takes a pointer to an int as boundary and updates the worth it focuses to 98.

Prototype: void reset_to_98(int *n);

1. Try not to trade ponies in crossing a stream

Compose a capability that trades the upsides of two numbers.

Prototype: void swap_int(int *a, int *b);

2. This report, by its actual length, protects itself against the gamble of being perused

Compose a capability that profits the length of a string.

Prototype: int _strlen(char *s);
FYI: The standard library gives a comparative capability: strlen. Run man strlen to find out more.

3. I don't fear PCs. I dread the absence of them

Compose a capability that prints a string, trailed by another line, to stdout.

Prototype: void _puts(char *str);
FYI: The standard library gives a comparative capability: puts. Run man puts to find out more.

4. I can go one way. I've not got an opposite gear

Compose a capability that prints a string, backward, trailed by another line.

Prototype: void print_rev(char *s);

5. A decent specialist thinks backward and gets some information about the elaborate results of the parts and frameworks he proposes

Compose a capability that inverts a string.

Prototype: void rev_string(char *s);

6. A portion of the untruths they tell about me aren't correct

Compose a capability that prints each and every person of a string, beginning with the primary person, trailed by another line.

Prototype: void puts2(char *str);

7. Winning is just 50% of it. It is the other half to Have a good time

Compose a capability that prints half of a string, trailed by another line.

Prototype: void puts_half(char *str);
The capability ought to print the last part of the string
Assuming the quantity of characters is odd, the capability ought to print the keep going n characters of the string, where n = (length_of_the_string - 1)/2

8. Clusters are not pointers

Compose a capability that prints n components of a variety of whole numbers, trailed by another line.

Prototype: void print_array(int *a, int n);
where n is the quantity of components of the cluster to be printed
Numbers should be isolated by comma, trailed by a space
The numbers ought to be shown in similar request as they are put away in the exhibit
You are permitted to utilize printf

9. strcpy

Model: singe *_strcpy(char *dest, burn *src);
Compose a capability that duplicates the string highlighted by src, including the ending invalid byte (\0), to the cushion highlighted by dest.

Bring esteem back: the pointer to dest
FYI: The standard library gives a comparative capability: strcpy. Run man strcpy to find out more.

10. Incredible pioneers will forfeit the numbers to save individuals. Unfortunate pioneers penance individuals to save the number
Compose a capability that convert a string to a number.

Prototype: int _atoi(char *s);
The number in the string can be gone before by a limitless number of characters
You want to consider all the - and + signs before the number
On the off chance that there are no numbers in the string, the capability should bring 0 back
You are not permitted to utilize long
You are not permitted to proclaim new factors of "type" exhibit
You are not permitted to hard-code extraordinary qualities
We will utilize the - fsanitize=signed-number flood gcc banner to aggregate your code.
FYI: The standard library gives a comparative capability: atoi. Run man atoi to find out more.

11. Try not to detest the programmer, can't stand the code

Make a program that creates irregular legitimate passwords for the program 101-crackme.

You are permitted to utilize the standard library
You don't need to breeze through the betty-style assessments (you actually need to finish the betty-doc assessments)
man srand, rand, time
gdb and objdump can help
