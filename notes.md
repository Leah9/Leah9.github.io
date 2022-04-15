# Markdown

https://www.markdownguide.org/cheat-sheet/

# C#

    using System;

    namespace HelloWorld
    {
      class Program
      {
        static void Main()
        {
          Console.WriteLine("Hello Leah");    
         }
        
        static string DefineMethod(parameter1, parameter2) // string defines return type
         {
           string output = "result";
           return output;

         }


      }
    }

## Conditionals
    int num = 1;

    if( num == 1 && true){
        Console.WriteLine("If statement");
        }
        else if (num == 2){
            Console.WriteLine("Dont forget capital L");
        }
        else {
            Something
        }

    switch (num)
    {
      case 1:
        Some action;
        break; // exit switch statement
      case 2:
        Another action;
        break;
      default:          //required
        If no other actions performed;
        break;
    }

    Ternary Operator... if else on one line.
    string color = "blue";
    string result = (color == "blue") ? "blue" : "NOT blue";

      int pepperLength = 4;
      string message = (pepperLength >= 3.5) ? "ready!": "wait a little longer";
      Console.WriteLine(message); //prints ready!

    double pow_ab = Math.Pow(6, 2); 
    Console.WriteLine(pow_ab);
    .toUpper()

    string example   = "Hi There!";
    string uppercase = example.ToUpper();
    // Result: "HI THERE!"

    string str = "Divyesh"; 
    int length = str.Length;
 
    // Finding the index of character  
    // which is present in string and 
    // this will show the value 5 
    int index1 = str.IndexOf('s');

    string myString = "Divyesh";
    string test1 = myString.Substring(2);

    // Concatenate two string variables    
    string name = firstName + " " + lastName;    
    Console.WriteLine(name);
    //Ths code will output Divyesh Goardnan

    
    // Call ToLower instance method, which returns a new copy.
    string lower = mixedCase.ToLower();
    //variable lower contains "this is a mixed case string."

    string a = "One example";
    Console.WriteLine("LENGTH: " + a.Length);
    // This code outputs 11

    // We can use an expression with a string interpolation.
    string multipliedNumber = $"The multiplied ID is {id * 10}.";
    Console.WriteLine(multipliedNumber);
    // This code would output "The multiplied ID is 1000."

    Console.WriteLine("Enter your name: "); 
    name = Console.ReadLine();
 

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

# JavaScript
We can use a ternary operator to perform the same functionality:

isNightTime ? console.log('Turn on the lights!') : console.log('Turn off the lights!');

In the example above:

    The condition, isNightTime, is provided before the ?.
    Two expressions follow the ? and are separated by a colon :.
    If the condition evaluates to true, the first expression executes.
    If the condition evaluates to false, the second expression executes.

Like if...else statements, ternary operators can be used for conditions which evaluate to true or false.

# G++ Compiler Windows
https://www.msys2.org
after install do the following
pacman -Syu
pacman -Su
pacman -S --needed base-devel mingw-w64-x86_64-toolchain

Add path msys64\mingw64\bin to user
restart terminal
In Visual code, Terminal > Run Build Task


# FizzBuzz in C my solution

#include <stdio.h>
int main(){
for (int i = 1; i <= 100; i++){
  
  if (i % 3 == 0 && i % 5 == 0){
    printf("FizzBuzz\n");
    } else if (i % 3 == 0){
    printf("Fizz\n");
    } else if (i % 5 == 0){
    printf("Buzz\n");
    } else {
      printf("%d\n", i);
    }
}
}

# Visual Code Extensions

    *GitLens
      Git integration
    *LiveShare
      Colaborative working
    *Pieces
      Code snipping and OCR
    *Better Comments
      Custom comments, colours etc
    *Turbo Console Log
      Automate create and remove console.log 
    *Code Runner
    *Import Cost - Displays size of includes
    *Prettier
    *ESLint - Javascript
    *Docker

# SQLite

Binaries for SQLite can be installed at the SQLite Download page.
Windows

For Windows machines:

    Download the sqlite-tools-win32-x86-3200100.zip file and unzip it.
    From your git-bash terminal, open the directory of the unzipped folder with cd ~/Downloads/sqlite-tools-win32-x86-3200100/sqlite-tools-win32-x86-3200100/.
    Try running sqlite with the command winpty ./sqlite3.exe. If that command opens a sqlite> prompt, congratulations! You’ve installed SQLite.

We want to be able to access this command quickly from elsewhere, so we’re going to create an alias to the command. Exit the sqlite> prompt by typing in Ctrl + C, and in the same git-bash terminal without changing folders, run these commands:

echo "alias sqlite3=\"winpty ${PWD}/sqlite3.exe\"" >> ~/.bashrc

and

source ~/.bashrc

The first command will create the alias sqlite3 that you can use to open a database. The second command will refresh your terminal so that you can start using this command. Try typing in the command sqlite3 newdb.sqlite. If you’re presented with a sqlite> prompt, you’ve successfully created the sqlite3 command for your terminal. Enter Ctrl + C to quit. You can also exit by typing .exit in the prompt and pressing Enter.
