# Basics-
A. Multiplication Table using 'for' loop.                                                                                                                                                                            
The program takes a number and a limit as input and then prints the multiplication table for that number up to the given limit.                                                                                      
Algorithm :

1. Create integer variables 'number', 'limit', and 'multiplier' to store user inputs.
2. Display "Enter the number - ".
3. Read and store the entered number in the 'number' variable.
4. Display "Enter limit - ".
5. Read and store the entered limit in the 'limit' variable.
6. Use a 'for' loop with 'multiplier' ranging from 1 to 'limit' (inclusive):
   a. Inside the loop, display the result of the multiplication in the format "number * multiplier = result".
      - Calculate the result as 'number * multiplier'.
      - Print this line.
7. End of the program.                                                                                                                                                                                                


B. Multiplication Table using 'while' loop.                                                                                                                                                                              
The program takes a number and a limit as input and then prints the multiplication table for that number up to the given limit using a while loop.                                                                        
Algorithm:

1. Create integer variables 'number', 'limit', 'multiplier', and 'counter' to store user inputs and loop control.
2. Display "Enter the number - ".
3. Read and store the entered number in the 'number' variable.
4. Display "Enter limit - ".
5. Read and store the entered limit in the 'limit' variable.
6. Initialize 'counter' to 1.
7. Use a 'while' loop with the condition 'counter <= limit':
   a. Inside the loop:
      - Display the result of the multiplication in the format "number * counter = result".
        - Calculate the result as 'number * counter'.
        - Print this line.
      - Increment 'counter' by 1.
8. End of the program.


C. Display 2 digit number in words.
The program takes a two-digit number as input and then prints the English words for each digit using a switch statement.                                                                                              
Algorithm :

1. Create integer variables 'dig', 'rem', 'q' to store user input and calculations.
2. Display "Enter a two-digit number - ".
3. Read and store the entered number in the 'dig' variable.
4. Calculate 'q' by dividing 'dig' by 10.
5. Calculate 'rem' by taking the remainder of 'dig' divided by 10.

6. Use a loop with 'i' ranging from 0 to 1 (to process both digits):
   a. Inside the loop, use a switch statement to convert 'q' to English words for the tens place:
      - For each case (0 to 9), print the corresponding English word.
   b. Set 'q' to 'rem' to process the units place in the next iteration.

7. End of the program.                                                                                                                                                                                              


D. Display a digit in words                                                                                                                                                                                            
The program takes a digit as input and then prints the English word for that digit using a switch statement.                                                                                                       
Algorithm:

1. Create an integer variable 'dig' to store user input.
2. Display "Enter a digit - ".
3. Read and store the entered digit in the 'dig' variable.
4. Use a switch statement to convert 'dig' to English words for digits:
   a. For each case (0 to 11), print the corresponding English word.
5. End of the program.
                                                                                                                                                                                                                  
                                                                                                                                                                                                                              
E. Bit Shifting                                                                                                                                                                                                         
The program reads an integer number and then left-shifts it by 8 bits to create a new integer newnumber.                                                                                                              
Algorithm:

1. Create integer variables 'number' and 'newnumber' to store user input and the result.
2. Display "Enter a number: ".
3. Read and store the entered number in the 'number' variable.
4. Perform a left shift operation on 'number' by 8 bits and store the result in 'newnumber'.
5. Display "New number after left shift: " followed by the value of 'newnumber'.
6. End of the program.                                                                                                                                                                                              
                                                                                                                                                                                                                    
F. Reverse a number                                                                                                                                                                                                  
The program reverses the digits of an input number.                                                                                                                                                                  
Algorithm:

1. Create integer variables 'number', 'remainder', 'newnumber', and 'counter' to store user input and calculations.
2. Display "Enter the number - ".
3. Read and store the entered number in the 'number' variable.
4. Initialize 'newnumber' to 0.
5. Use a 'for' loop with 'counter' ranging from 4 to 1 (inclusive):
   a. Inside the loop:
      i. Calculate 'remainder' by taking the remainder of 'number' when divided by 10.
      ii. Update 'number' by dividing it by 10.
      iii. Print 'remainder'.
      iv. Calculate the contribution of 'remainder' to 'newnumber' by multiplying it with 10^(counter-1).
      v. Add the contribution to 'newnumber'.
6. Print the final value of 'newnumber' as the reversed number.
7. End of the program.
                                                                                                                                                                                                                    
                                                                                                                                                                                                                      
G. Basic Operations on two integer inputs.
The program takes three integer inputs (Var1, Var2, and Var3), performs various mathematical operations.                                                                                                                
It assigns a new value to Var3. Here's the algorithm for your program:                                                                                                                                              
Algorithm:

1. Create integer variables 'Var1', 'Var2', and 'Var3' to store user inputs.
2. Display "Enter number 1 - ".
3. Read and store the entered number in 'Var1'.
4. Display "Enter number 2 - ".
5. Read and store the entered number in 'Var2'.
6. Calculate the sum of 'Var1' and 'Var2' and display "Sum of given inputs = " followed by the result.
7. Calculate the difference between 'Var1' and 'Var2' and display "Difference of given inputs = " followed by the result.
8. Calculate the product of 'Var1' and 'Var2' and display "Product of given inputs = " followed by the result.
9. Calculate the division of 'Var1' by 'Var2' (assuming 'Var2' is not zero) and display "Division of given inputs = " followed by the result.
10. Display "Enter number 3 - ".
11. Read and store the entered number in 'Var3'.
12. Add 'Var2' to 'Var3' and assign the result back to 'Var3'. Display "Assignment = " followed by the result.
13. End of the program.
                                                                                                                                                                                                                    
                                                                                                                                                                                                                    
                                                                                                                                                                                                                   
