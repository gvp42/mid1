# **_GAYATRI VIDYA PARISHID COLLEGE OF ENGINEERING (AUTONOMOUS)_**

## **PPSUC MID-1 ANSWERS 2021-22
## (SIMPLE VERSION)**

**1(a)  Explain different types of problem-solving strategies (5M)**

**Ans:** There are several problem-solving strategies that can be used to solve different types of problems. Here are a few examples:


1. Trial and error: This strategy involves trying different solutions until you find one that works. It can be helpful for solving problems that have multiple possible solutions or for problems where the best solution is not immediately obvious.


2. Algorithmic: This strategy involves using a step-by-step approach to solving a problem. It is often used in mathematical and computer science problems and involves breaking the problem down into smaller, more manageable steps.


3. Heuristic: This strategy involves using rules of thumb or educated guesses to solve problems. It can be useful for solving problems where there is no clear solution or for problems where the best solution is not immediately apparent.


4. Lateral thinking: This strategy involves looking at a problem from a different perspective and using creative thinking to find a solution. It can be useful for solving problems that require a unique or innovative solution.


5. Divide and conquer: This strategy involves breaking a problem down into smaller, more manageable parts and solving each part separately. It can be helpful for solving complex problems or problems that involve multiple components.


6. Root cause analysis: This strategy involves identifying the underlying cause of a problem and addressing it directly. It can be useful for solving problems that have recurring or persistent issues.


These are just a few examples of problem-solving strategies. The best strategy to use will depend on the specific problem you are trying to solve and the resources you have available.


**1 (b) Define a flowchart? Draw a flowchart to find a given integer is even or odd (5M)**

**Ans:** A flowchart is a graphical representation of a process or algorithm. It uses different shapes and arrows to show the flow of steps and decisions in a process.


Here's a simple flowchart that checks whether a given integer is even or odd:


```
+--------------+        +--------------+
|   Start      |        |  Number is   |
|              |        |   Even       |
+--------------+        +--------------+
        |                         |
        | Yes                     | No
        |                         |
+--------------+        +--------------+
|    Input     |        |  Number is   |
|   Number     |------->|    Odd       |
+--------------+        +--------------+
        |                         |
        | Done                    | Done
        |                         |
+--------------+        +--------------+
|    Stop      |        |    Stop      |
+--------------+        +--------------+
```


In this flowchart, the process starts with the "Start" symbol and then prompts the user to input a number. The flow then continues to the diamond-shaped decision symbol where it checks whether the number is even or odd. If the number is even, the flow proceeds to the "Number is Even" symbol and stops. If the number is odd, the flow proceeds to the "Number is Odd" symbol and stops. Finally, the process ends with the "Stop" symbol.


Note that there are many ways to design a flowchart to solve a particular problem, and the specific shapes used and the layout of the flowchart may vary depending on the problem being solved and the preferences of the person creating the flowchart.


2**(a) What is an algorithm? Write algorithm for swapping of two
Numbers and analyze with example (5M)**

**Ans:** An algorithm is a step-by-step procedure that outlines how to solve a particular problem or accomplish a specific task. It's a series of instructions that a computer can understand and execute to achieve a desired outcome.


Here is an algorithm for swapping two numbers:


```
Step 1: Input the two numbers A and B.
Step 2: Create a temporary variable called temp.
Step 3: Assign the value of A to temp.
Step 4: Assign the value of B to A.
Step 5: Assign the value of temp to B.
Step 6: Output the swapped values of A and B.
```


Let's analyze this algorithm with an example. Suppose we want to swap the values of A = 5 and B = 9.


- Step 1: We input A = 5 and B = 9.
- Step 2: We create a temporary variable called temp.
- Step 3: We assign the value of A (which is 5) to temp, so temp = 5.
- Step 4: We assign the value of B (which is 9) to A, so A = 9.
- Step 5: We assign the value of temp (which is 5) to B, so B = 5.
- Step 6: We output the swapped values of A and B, which are A = 9 and B = 5.


In conclusion, this algorithm swaps the values of A and B by temporarily storing the value of A in a variable called temp, assigning the value of B to A, and then assigning the value of temp to B. This algorithm can be used to swap the values of any two variables.


**2(b) Explain the steps involved in problem solving (5M)**

**Ans:** An algorithm is a step-by-step procedure that outlines how to solve a particular problem or accomplish a specific task. It's a series of instructions that a computer can understand and execute to achieve a desired outcome.


Here is an algorithm for swapping two numbers:


```
Step 1: Input the two numbers A and B.
Step 2: Create a temporary variable called temp.
Step 3: Assign the value of A to temp.
Step 4: Assign the value of B to A.
Step 5: Assign the value of temp to B.
Step 6: Output the swapped values of A and B.
```


Let's analyze this algorithm with an example. Suppose we want to swap the values of A = 5 and B = 9.


- Step 1: We input A = 5 and B = 9.
- Step 2: We create a temporary variable called temp.
- Step 3: We assign the value of A (which is 5) to temp, so temp = 5.
- Step 4: We assign the value of B (which is 9) to A, so A = 9.
- Step 5: We assign the value of temp (which is 5) to B, so B = 5.
- Step 6: We output the swapped values of A and B, which are A = 9 and B = 5.


In conclusion, this algorithm swaps the values of A and B by temporarily storing the value of A in a variable called temp, assigning the value of B to A, and then assigning the value of temp to B. This algorithm can be used to swap the values of any two variables.


**3(a)Explain the Structure of C program with an example program. (5M)**

**Ans:**A C program typically consists of several parts, including:


1. Preprocessor Directives: These are special commands that begin with a # symbol and are used to provide instructions to the C preprocessor. They are typically used to include header files, define macros, or conditionally compile code.


2. Function Prototypes: These are declarations of functions that specify the function's return type, name, and parameter list. They are typically placed at the beginning of a program to provide a clear understanding of the functions being used.


3. Global Variables: These are variables that are declared outside of any function and can be accessed by any part of the program. They are typically used to store data that needs to be shared across multiple functions.


4. Main Function: This is the entry point of a C program and is where the program starts executing. The main function typically contains declarations of local variables, function calls, and the program's main logic.


Here is a simple example C program that demonstrates this structure:


```
#include <stdio.h>


int main() {
   printf("Hello, world!\n");
   return 0;
}
```


In this example, we include the standard input/output header file using a preprocessor directive. 


Then, we define the main function which prints the string "Hello, world!" using the `printf` function and returns 0 to indicate that the program has executed successfully.


Overall, this example demonstrates the basic structure of a C program, including the use of preprocessor directives, the main function, and a function call.


**3(b) Illustrate the differences between while and do-while with example (5M)**
**Ans:** The `while` and `do-while` loops are used in C programming language to repeat a block of code based on a certain condition. However, the key difference between them is the order in which the condition is checked.


In a `while` loop, the condition is checked at the beginning of the loop. If the condition is true, the loop body will be executed. If the condition is false, the loop will be skipped entirely. Here is an example:


```
int i = 0;
while (i < 5) {
   printf("%d ", i);
   i++;
}
```


In this example, the loop condition `i < 5` is checked before the loop body is executed. If `i` is less than 5, the loop body is executed which prints the value of `i` and increments it by 1. This process is repeated until `i` is no longer less than 5.


On the other hand, in a `do-while` loop, the condition is checked at the end of the loop. This means that the loop body is guaranteed to execute at least once, regardless of whether the condition is true or false. Here is an example:


```
int i = 0;
do {
   printf("%d ", i);
   i++;
} while (i < 5);
```


In this example, the loop body is executed at least once, printing the value of `i` and incrementing it by 1. Then, the loop condition `i < 5` is checked. If the condition is true, the loop body is executed again and the process repeats. If the condition is false, the loop is exited.


In summary, the main difference between `while` and `do-while` is that `while` checks the condition before executing the loop body, while `do-while` checks the condition after executing the loop body at least once.



**4. Define a function? List out the categories of functions with example program(10M)**

**Ans:** In C programming language, a function is a block of code that performs a specific task and can be called from other parts of the program. Functions can help to make programs more modular, easier to read, and easier to debug. A function typically has a name, a return type, a parameter list, and a body of code.


Here is an example of a simple function that calculates the sum of two integers:


```
int add(int a, int b) {
   int sum = a + b;
   return sum;
}
```


This function is called `add` and takes two integers `a` and `b` as parameters. It calculates the sum of `a` and `b` and returns the result as an integer.


Functions in C can be categorized into several types based on their purpose and return type. Here are some examples:


1. Void Functions: These functions do not return any value. They are used to perform a specific task without returning a value. Example:


```
void greet() {
   printf("Hello, World!");
}
```


This function simply prints the message "Hello, World!" to the screen.


2. Functions with Return Value: These functions return a value of a specific data type. Example:


```
int square(int x) {
   return x * x;
}
```


This function takes an integer `x` as input, calculates its square, and returns the result as an integer.


3. Recursive Functions: These functions call themselves, either directly or indirectly. Example:


```
int factorial(int n) {
   if (n == 0) {
      return 1;
   } else {
      return n * factorial(n - 1);
   }
}
```


This function calculates the factorial of a number `n` using recursion.


4. Library Functions: These functions are predefined in standard libraries and can be used by the programmer without defining them. Example:


```
#include <stdio.h>


int main() {
   printf("Hello, World!");
   return 0;
}
```


The `printf` function is a library function that is defined in the `stdio.h` header file. It is used here to print the message "Hello, World!" to the screen.



**5(a)   Explain the construction of loops with basic programming constructs. (5M)**

**Ans:** Loops are used in computer programming to repeat a set of instructions multiple times. The basic constructs used to create loops are the loop control variable, the loop condition, and the loop body.

The loop control variable is a variable used to keep track of the number of times the loop has been executed. The loop condition is a statement that checks whether the loop should continue or stop. The loop body is a set of instructions that are executed each time the loop is executed.

There are two main types of loops: "while" loops and "for" loops. A "while" loop will execute the loop body as long as the loop condition is true. A "for" loop is a variation of the "while" loop and is used when the number of iterations is known in advance.

Loops can also be nested, meaning that one loop can be placed inside another loop. This allows more complex instructions to be executed multiple times.

Overall, loops are a powerful tool in programming that allow a set of instructions to be executed multiple times, making code more efficient and reducing the amount of repetitive code needed.


**5(b)   Write a c program to perform arithmetic operations using switch statement    (5M)**

**Ans:** Here's a simple C program that performs arithmetic operations using a switch statement:

```
#include <stdio.h>

int main() {
   char operator;
   double num1, num2, result;

   printf("Enter an operator (+, -, *, /): ");
   scanf("%c", &operator);

   printf("Enter two numbers: ");
   scanf("%lf %lf", &num1, &num2);

   switch(operator) {
  	case '+':
     	result = num1 + num2;
     	break;
  	case '-':
     	result = num1 - num2;
     	break;
  	case '*':
     	result = num1 * num2;
     	break;
  	case '/':
     	result = num1 / num2;
     	break;
  	default:
     	printf("Error: Invalid operator.");
     	return 0;
   }

   printf("%.2lf %c %.2lf = %.2lf", num1, operator, num2, result);
   return 0;
}
```

This program first prompts the user to enter an operator, and then two numbers. It then uses a switch statement to perform the arithmetic operation based on the operator entered. The result is then displayed to the user.


**6(a)  Explain about program design and implementation issues in problem solving (5M).**

**Ans: **Program design and implementation refer to the process of creating a software program that solves a specific problem. This process involves several important issues that must be considered to create an effective program.

Program design involves determining the requirements of the program, such as what it should do and how it should do it. This includes identifying the inputs and outputs of the program, as well as any constraints or limitations that must be taken into account. Once the requirements are determined, the program can be designed, which involves breaking the problem down into smaller, more manageable parts. This may involve creating flowcharts, pseudocode, or other types of diagrams to help visualize the program's structure.

Implementation refers to the actual coding of the program, where the design is translated into actual code using a programming language. This involves selecting the appropriate data structures, algorithms, and programming constructs to create a working program that meets the design requirements. During implementation, the program must be tested and debugged to ensure that it works correctly and efficiently.

Some common issues that must be considered during program design and implementation include:

- Efficiency: The program should be designed and coded in such a way that it runs quickly and uses minimal system resources.

- Reliability: The program should be designed and coded to be as error-free as possible, and any errors that do occur should be handled gracefully.

- Scalability: The program should be designed and coded in such a way that it can be easily modified or expanded as needed.

- Maintainability: The program should be designed and coded in such a way that it can be easily maintained and updated over time.

- Usability: The program should be designed and coded in such a way that it is easy to use and understand for the end user.

Overall, program design and implementation involve a complex process of planning, coding, testing, and refining to create a high-quality software program that effectively solves a specific problem.
(or)
Program design and implementation refer to the process of creating a software program that solves a specific problem. This involves determining the requirements of the program, breaking down the problem into smaller, more manageable parts, and then coding the program using a programming language. The program must be tested and debugged to ensure that it works correctly and efficiently. Issues that must be considered include efficiency, reliability, scalability, maintainability, and usability. Overall, program design and implementation require a complex process of planning, coding, testing, and refining to create a high-quality software program that effectively solves a specific problem.


**6(b)   Explain about parameter passing techniques in detail .                              (5M)**


**Ans:**Parameter passing is the process of transferring data or values between different parts of a program, such as between a function and its caller. There are several ways to pass parameters in programming, each with its own benefits and drawbacks.

1. Pass by value: In this technique, the value of the parameter is copied and passed to the function. Any changes made to the parameter within the function do not affect the original value outside the function. This technique is easy to use and fast, but it can be slower and use more memory if the data being passed is large.

2. Pass by reference: In this technique, a reference or pointer to the parameter is passed to the function. Any changes made to the parameter within the function affect the original value outside the function. This technique can be faster and use less memory than pass by value, but it can also be more error-prone and harder to understand.

3. Pass by pointer: This technique is similar to pass by reference, but uses pointers instead of references. Pointers can be used to point to any type of data, including arrays and structures.

4. Pass by name: In this technique, the actual parameter is substituted into the function call at runtime. This technique is more flexible than pass by value, but it can be slower and harder to understand.

5. Pass by value-result: This technique is a combination of pass by value and pass by reference. The parameter is passed by value, but any changes made to the parameter within the function are passed back to the caller when the function returns. This technique is useful when the function needs to modify the original parameter but does not want to affect other variables that may be referencing the original parameter.

The choice of parameter passing technique depends on the specific needs of the program and the type of data being passed. It is important to understand the advantages and disadvantages of each technique to choose the most appropriate one for the task at hand.

****		