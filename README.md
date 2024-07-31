Question-1 What are the conditional Operators in Java?
Soltion-



Conditional Operators in Java
1. Ternary Operator (?:)
Purpose: A shorthand for the if-else statement.
Syntax: condition ? expression1 : expression2
Explanation: If condition is true, expression1 is executed. Otherwise, expression2 is executed.
Example:
java
Copy code
int a = 10;
int b = 20;
int max = (a > b) ? a : b;
// max will be 20 because the condition (a > b) is false.
2. Logical AND Operator (&&)
Purpose: To combine two boolean expressions.
Syntax: expression1 && expression2
Explanation: The result is true if both expression1 and expression2 are true.
Example:
java
Copy code
boolean a = true;
boolean b = false;
boolean result = a && b;
// result will be false because b is false.
3. Logical OR Operator (||)
Purpose: To combine two boolean expressions.
Syntax: expression1 || expression2
Explanation: The result is true if at least one of expression1 or expression2 is true.
Example:
java
Copy code
boolean a = true;
boolean b = false;
boolean result = a || b;
// result will be true because a is true.
Summary
Ternary Operator (?:): Used for simple if-else conditions.
Logical AND Operator (&&): True only if both operands are true.
Logical OR Operator (||): True if at least one operand is true.

Question 2-What are the types of Operators based on the number of operands?
solution-Unary Operators
Binary Operators
Ternary Operators

Question 3 -What is the use of switch case in programming
The switch statement in programming is used for executing one out of many code blocks based on the value of a variable or an expression. It's a more readable and organized way to handle multiple conditions compared to a series of if-else statements. 
switch (expression) {
    case value1:
        // code to be executed if expression == value1
        break;
    case value2:
        // code to be executed if expression == value2
        break;
    ...
    default:
        // code to be executed if expression doesn't match any case
}

Question 4-What are the priority levels of arithmatic operation in java?
In Java, the precedence (priority) of arithmetic operators determines the order in which the operations are performed in an expression. When multiple operators are used in a single expression, the operations with higher precedence are performed first. If operators have the same precedence, their associativity (left-to-right or right-to-left) determines the order of execution.

Arithmetic Operators and Their Precedence
Here is a list of arithmetic operators in Java, ordered by their precedence from highest to lowest:

Unary Plus and Minus (+, -)

Description: Unary operators for indicating positive and negative values.
Associativity: Right-to-left
Example: -a, +b
Multiplicative Operators (*, /, %)

Description: Multiplication, division, and modulus.
Associativity: Left-to-right
Example: a * b, a / b, a % b
Additive Operators (+, -)

Description: Addition and subtraction.
Associativity: Left-to-right
Example: a + b, a - b


Question -5 What are the conditional statement in java along with its uses ?

Conditional statements in Java control the flow of execution based on specific conditions. They allow the program to make decisions and execute certain blocks of code depending on whether the condition is true or false. The main conditional statements in Java are:

if statement
if-else statement
if-else-if ladder
nested if statement
switch statement

Question 6- What is the Syntax of if else statement?
Answer-
if(codition){
    //body of if block
}
else{
    //body of else block
}
Question 7-What are the three types of iterative statementsi in java?
Answer -
if-else
if-else if-else
nested if 

Question 8-What is the difference between for and do-while loop?
Answer 
for (initialization; condition; update) {
    // code to be executed
}

do {
    body
}while(condition);
difference is for  will run only if condition is true nut do whike will run atleast one time ::

Question 9-Print numbers from 1 to 10
solution

public class Main {
    public static void main(String[] args) {
        for (int i = 1; i <= 10; i++) {
            System.out.println(i);
        }
    }
}
