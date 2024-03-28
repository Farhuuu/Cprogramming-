# Cprogramming-
A C programming code in ubuntu 

#include <stdio.h>
int main(void) {
/* This is my first program in C */
printf(“Hello World!”);
printf(“I Love C”);
return (0);
}



//user input code
1. Open up a terminal.

2. Create a file called userinput.c by using nano text editor.
nano userinput.c

3. Type in the following program segment:
#include <stdio.h>
int main(void) {
/* This is my second program in C */
int age;
printf(“Hi, how old are you? > ”);
scanf(“%d”, &age);
printf(“You are %d years old”, age);
return (0);
}
