# Aim: To study and implement C++ decision making statements Loops
# Software Required :

Visual Studio

# Theory:
Different Types of Loops C++ provides three types of loops that works the same, but are preferred in different use cases:

# For Loop:
The for loop is an entry-controlled loop, which means that it checks whether the test condition is true before executing the statements inside it. The various parts of the for loop are:

Initialization: Initialize the variable to some initial value.
Test Condition: This specifies the test condition. If the condition evaluates to true, then body of the loop is executed. If evaluated false, loop is terminated.
Update Expression: After the execution loop's body, this expression increments/decrements the loop variable by some value. All these together is used to create a logic and flow of the loop.

# While Loop:

The while loop is also an entry-controlled loop which is used in situations where we do not know the exact number of iterations of the loop beforehand.

In for loop, we have seen that the number of iterations is known beforehand, i.e. the number of times the loop body is needed to be executed is known to us and we create the condition on the basis of it. But while loops execution is solely based on the condition.


# Do-While Loop
The do-while loop is an exit-controlled loop which means the condition is checked after executing the body of the loop. So, in a do-while loop, the loop body will execute at least once irrespective of the test condition.


# Infinite Loops:

An infinite loop (sometimes called an endless loop) is a piece of coding that lacks a functional exit so that it repeats indefinitely. An infinite loop occurs when a condition is always evaluated to be true.

# Nesting of Loops:

Nesting of loops refers to placing one loop inside another. The inner loop is executed completely for each iteration of the outer loop. This is useful when you need to perform multiple iterations within each iteration of a larger loop, such as iterating over a two-dimensional array or performing operations that require more than one level of iteration.

# Implementation:

The Logic and conditional flow of the statements were seen through the following programs :

Printing even numbers from 1 to 10
reversing of integer values
Simple login through password
Patterns
# Algorithm: 

Printing even numbers from 1 to 10:

1.Start

2.create a for loop from 1 to 10

3. if i %2=0

4. display i

5. end

Reversing of intger value:

1.start

2.declare num and reversed =0

3.while num !=0

int digit=num%10

reversed=reversed *10+digit

num=num/10

4. display reversed number

5. end

Printing simple pyramid

1.start

2.declare n=5

3.for(int i=1;i<=n;i++) and for(int j=1;j<=n;j++)

4 print'*' in the new lines

5.end

Printing Floyd's Series:

1.start

2.declare n=4 and num = 1

3.for(int i=0;i<n;i++) and for(int j=0;j<n;j++)

4. display " " and num

5. num++

6. end


# Conclusion:
Through the programs , The logic and operation of loops in C++ has been studied.
