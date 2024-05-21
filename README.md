# c-programming-concepts

## Chapter 1 - Variables, Data types + Input/Output

1. Variables ✔
2. Keywords ✔
3. Constants ✔
4. Comments✔
5. Structure ✔
6. Compilation✔

- 💚 Variables: Variable is the name of a memory location which stores some data.
  Variables name convention or Rules:
- Variables are case sensitive
  1st character is alphabet or ‘_’
  No comma/blank space
  No other symbol other than ‘_’
  Data Types:
  💚 Constants: Values that don’t change (fixed)
  Types of Constants:
- Integer constants
  Real Constants
  Character Constants
  💚 Keywords: Reserved words that have special meaning to the compiler. 32 keywords in c programming language.
  💚 Comments: comments is important part programming which is give code maintain facility
  Single line comment
  Multi line comment
  ** Format Specifier **
  ** Escape Sequence**
  💚 Compilation: A computer program that translates C code into machine code.

## Chapter 2 - Instructions & Operators

### Instructions -> These are statements in a program.
- Types of Instructions:
    1. Type Declaration Instructions ___ Declare variable before using it
    2. Arithmetic Instructions ____ Note: single variable on the LHS
    3. Control Instructions

    * Type Conversion
        1. implicit conversion
        2. explicit conversion
    * Operator Precedence
        0. brackets
        1. *, /, %
        2. +, -
        3. =
        N.B -> Associativity (for same precedence): Left to Right
### Control Instructions-> used to determine flow of program
    1. Sequence Control
    2. Decision Control = if else
    3. Loop control  = for, while, do ... while 
    4. Case Control = 

### 💚Operators 
    1. Arithmetic Operaors *
    2. Relational Operators * _____ ==, >, <, <=, >=, !=
    3. Logical Operaors * ______ &&, ||, !
    4. Bitwise Operators *^, &, | *
    5. Assignment Operators *** "=, +=, -=, *=, /=, %="
    6. Ternary Operators * expree? "express": express*


 
  ###  💚Operator Precedence 
        1. *, /, % -> high precendence operator
        2. +, - -> middle precendence operator
        3. = low precendence operator
    ✔ Associativity law = Left to Right


### 💚Operators Precendence in different type operators
    | Priority  | Operator              |
    |-----------|-----------------------|
    |    1      |         !             |
    |    2      |       *, /, %         |    
    |    3      |       + , -           |    
    |    4      |       <. <=, >, >=    |
    |    5      |       ==, !=          |
    |    6      |           &&          |
    |    7      |           ||          |
    |    8      |           =           |

/*
Author: Abu Bakar
May 1, 2024
c programming structure
*/

```#include<stdio.h> //preprocessor directive
    int main(){ //main function c program execution start at this point
    
        int a;
        printf("Enter a side for square area calculation: ");
        scanf("%d", &a);
        printf("The area of square is %d", a*a);
        return 0;
    }
```
/* 
Author: Abu Bakar
May 16, 2024
c programming structure
*/

```#include<stdio.h>
    int main(){
    
    int a = 5*2 - 2*3; // = 10 - 6 = 4
    
    int b = 5*2 / 2*3; // = 10 / 2 * 3 = 5 *3 = 15
    
    int c = 5* (2/2)*3; // = 5 * 1 * 3 = 15
    
    int d = 5 + 2 / 2 * 3; // = 5  + 1 * 3 = 8
    
    
    printf("a is equal= %d\n", a);
    printf("b is equal= %d\n", b);
    printf("c is equal= %d\n", c);
    printf("d is equal= %d\n", d);
    
        return 0;
    }
```

/*
Author: Abu Bakar
May 21, 2024
c programming structure
*/

```// Example 01
    #include<stdio.h>
    int main(){
        int a, b, sum=0;
    
        // show message for collecting input
        printf("Enter a number: ");
        scanf("%d", &a);// collecting and storing number in variable a
        printf("Enter a number: ");
        scanf("%d", &b);
        sum = a + b;
        printf("Sum of your two numbers = %d", sum);
        return 0;
    }
```

```// Example 02
    #include<stdio.h>
    int main(){
        
        int number;
    
        printf("Enter a number: ");
        scanf("%d", &number);
        if(number % 2 != 0 ){
            printf("NOt Divisible");
        }
        else{
           printf("Divisible"); 
        }
        return 0;
    }
```

```// Example 03

    #include<stdio.h>
    int main(){
        
        int number;
    
        printf("Enter a number: ");
        scanf("%d", &number);
        if(number % 2 != 0 ){
            printf("Odd number");
        }
        else{
           printf("Even number"); 
        }
        return 0;
    }
```

```// Example 04

      #include<stdio.h>
      int main(){
          
          int number;
      
          printf("Enter a number: ");
          scanf("%d", &number);
          if(number> 9 && number < 100){
              printf("Two digit number");
          }
          else{
             printf("Not two digit number"); 
          }
          return 0;
      }
```

```// Example 05
    #include<stdio.h>
    int main(){
        
       int a, b, c;
       float average;
    
       printf("Enter first number: ");
       scanf("%d", &a);
    
       printf("Enter second number: ");
       scanf("%d", &b);
    
       printf("Enter third number: ");
       scanf("%d", &c);
    
       average = (a + b +c)/3;
    
       printf("Average of 3 number %f", average);
        return 0;
    }
```

## Chapter 3 - Conditional Statements


