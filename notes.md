# Markdown

https://www.markdownguide.org/cheat-sheet/



# Python

    list = ["string", 2023, 5.67, True]

    dictionary = {"key": "value", "Name": "Leah", "Age": 41}

    variable = 124

    string = "string"

    float = 1.23

    def function(arg1, arg2):
        for i in range(0, 10, 1)
            some stuff
            i += 1
        return(variables)

    function(var, var)

    if variable == 123:
        print("The variable is 123)
    else:
        print("The variable = ", str(variable))

# C

    #include <stdio.h>
    
    End of line ;

    gcc filenamein.c -o progNameOut

    // Comment, above is include syntax
    /*multi
    line
    comment*/

    escape charactera \n newline \t tab \r carriage return

    int main() {
        if (value == value){
            printf("Values match\n");
        } else if (condition true){
            printf("Values are different\n");
        } else { //everything else and optional

        }

        switch (grade) {
         case 9:
          printf("Freshman\n");
          break;
         case 10:
          printf("Sophomore\n");
          break;
         default:
          break;
        
    }

    Ternary operators

    min = a < b ? a : b;
    if a is less than b ? then do the part this side of : else do this part;

    int 	a whole number 	-2,147,483,648 to 2,147,483,647
    float 	a number with possible decimals 	6 decimal places
    double 	a number with possible decimals 	15 decimal places
    char 	stores one character (letter or number) 	a single character

    char foo = 'a'
    float floaty = 1.23
    int day = 3;
    printf("Hello World, today is the %ird!", day);

    increment by 1 variable++ or var--
    a = 10
    b = 5
    c += b
    c = 15
    also -= /= *= %=

    Logical Operators
    && = and
    || = or
    != = not equal
    symbol 	type
    %d or %i 	int
    %f 	double or float
    %c 	char

    while Loops

while loops iterate until a condition is met.

    while (a < 10) {
      a++;
    }

do-while Loops

do-while loops are while loops that initially execute the body once before checking the condition.

    do {
      printf("not true!");
    } (while 2 == 3);

for Loops

for loops complete a set number of iterations before meeting a condition.

    for (int i = 0; i <= 10; i++) {
      printf("Hello!");
    }

Loop Keywords

All loops can utilize keywords like continue and break. continue restarts the loop and break breaks out of (or ends) the loop.
Rewriting Loops

A for loop can always be re-written as a while loop; most while loops can be re-written as a for loop.


# G++ Compiler Windows
https://www.msys2.org
after install do the following
pacman -Syu
pacman -Su
pacman -S --needed base-devel mingw-w64-x86_64-toolchain

Add path msys64\mingw64\bin to user
restart terminal
In Visual code, Terminal > Run Build Task