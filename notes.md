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

    gcc filenamein.c -o progNameOut

    // Comment, above is include syntax
    /*multi
    line
    comment*/

    escape charactera \n newline \t tab \r carriage return

    int main() {
        printf("Hello Leah!\n");
    }

    int 	a whole number 	-2,147,483,648 to 2,147,483,647
    float 	a number with possible decimals 	6 decimal places
    double 	a number with possible decimals 	15 decimal places
    char 	stores one character (letter or number) 	a single character

    char foo = 'a'
    float floaty = 1.23
    int day = 3;
    printf("Hello World, today is the %ird!", day);

    symbol 	type
    %d or %i 	int
    %f 	double or float
    %c 	char

# G++ Compiler Windows
https://www.msys2.org
after install do the following
pacman -Syu
pacman -Su
pacman -S --needed base-devel mingw-w64-x86_64-toolchain

Add path msys64\mingw64\bin to user
restart terminal
In Visual code, Terminal > Run Build Task