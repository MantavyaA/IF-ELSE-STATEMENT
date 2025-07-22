# IF-ELSE-STATEMENT

AIM : To study and implement C++ decision making statements

SOFTWARE USED : VS CODE

THEORY : In C++, decision-making is achieved through conditional statements, with if-else and switch-case being the most commonly used. The if-else construct is highly versatile and allows the program to evaluate expressions or conditions that result in either true or false. When the condition in an if statement is true, the corresponding block of code is executed. If the condition is false, the program can move to an else if block to check another condition, or to an else block to handle all remaining possibilities. This makes if-else ideal for handling complex logic involving inequalities, multiple variable comparisons, and compound logical conditions (using &&, ||, etc.).

The switch-case structure, in contrast, is typically used when a single variable or expression needs to be tested against several predefined constant values. Each possible value is represented by a case label, and the matching case executes its corresponding block of code. The break statement is used to terminate a case and prevent the program from unintentionally executing subsequent cases—a behavior known as "fall-through." If no case matches the value, the default block is executed, providing a catch-all for unmatched cases. Switch-case is especially effective for programs like calculators, menu-based applications, or selecting specific actions based on numeric or character input.

While both if-else and switch-case guide the program’s control flow, the choice between them depends on the situation. If-else offers more flexibility for conditions involving ranges, multiple variables, or complex logic, whereas switch-case is more readable and efficient when comparing a single variable against a list of fixed values. Together, these structures allow programmers to design interactive, logical, and user-driven applications by controlling which sections of code should be executed based on user input or specific program conditions.


ALGORITHM : 

1. Even or Odd Program


Start

Declare an integer variable number

Input a number from the user

Check if number % 2 == 0

If true, print "The number is even"

Else, print "The number is odd"

Stop



2. Vowel or Consonant Program

   
Start

Declare a character variable ch

Input a character from the user

Check if ch is a vowel (a, e, i, o, u in both upper and lowercase)

If true, print "The character is a vowel"

Else, print "The character is a consonant"

Stop



3.Largest Among Three Numbers


Start

Declare three integer variables: num1, num2, and num3

Input all three numbers

Compare the values:

If num1 > num2 and num1 > num3, print "Num1 is the largest"

Else if num2 > num1 and num2 > num3, print "Num2 is the largest"

Else, print "Num3 is the largest"

Stop

