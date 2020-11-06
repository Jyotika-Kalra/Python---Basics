### Week-01-in-a-go-

## Week01 learning with Code Academy Berlin: 

* **Installation of:**

  - Anaconda 
  - Visual Studio Code
  - Trello
  - Git Hub 

* **'Python'**
* **Introduction** - Python is an object-oriented, interpreted, high-level programming language with dynamic semantics.

* **Features of Python:** 
  - Interpreted language
  - Easy to use
  - Simple code writing
  - Readable to all
  - Portable
                      
* **Data Types:** 
  - Integer: 783, 0, -192
  - Float: 9.23, 0.2
  - Complex: 1 + 3h + 6j
  - Boolean: True, False
  - String: 1\t2\t3
  - Tuples: 11,"y",7.4
  - Sets: {1,9,3,0}
  - List: ['a','b','c']
             
* **Operator Types:** 
  - Arithmetic: +,-,/,%,*
  - Assignement: =,=+,-=,*=,/=,%=
  - Comparison: ==,!=,<,>,<=,>=
  - Logical: and, or, not
  - Bitwise: ^, <<, >>
  - Identity: is, is not
  - Membership: in, not in
          
* **Conditional and Loops**: A statement that controls the flow of execution depending on some condition. In Python the keywords if, elif, and else are used for conditional statements.
 - **The if statement:** An if statement is a programming conditional statement that, if proved true, performs a function or displays information.
  Example:
```
  food = 'spam'

if food == 'spam':
    print('Ummmm, my favorite!')
    print('I feel like saying it 100 times...')
    print(100 * (food + '! '))
```
    
   - **The if else statement:** The if/else statement executes a block of code if a specified condition is true. If the condition is false, another block of code can be executed. 
  Example:
  
 ```
 if food == 'spam':
    print('Ummmm, my favorite!')
else:
    print("No, I won't have it. I want spam!")
 ```
    
   - **Chained conditionals:** Briefly, If x < y: print("x is less than y") elif x > y: print("x is greater than y") else: print("x and y must be equal").
  Example:
  
 ```
  if x < y:
    STATEMENTS_A
elif x > y:
    STATEMENTS_B
else:
    STATEMENTS_C
 ```

  - **Nested conditionals:** A nested if is an if statement that is the target of another if statement. Nested if statements means an if statement inside another if statement.
 Example:
 
 ```
 if x < y:
    STATEMENTS_A
else:
    if x > y:
        STATEMENTS_B
    else:
        STATEMENTS_C
  ```
        
  - **The for loop:** A for loop is used for iterating over a sequence (that is either a list, a tuple, a dictionary, a set, or a string).
 Example: 

```
 for friend in ['Margot', 'Kathryn', 'Prisila']:
    invitation = "Hi " + friend + ".  Please come to my party on Saturday!"
    print(invitation)
 ```
    
   - **Range:** The range() function returns a sequence of numbers, starting from 0 by default, and increments by 1 (by default), and stops before a specified number.
  Example:
  
 ``` 
  >>> for i in range(5):
...     print('i is now:', i)
...
i is now 0
i is now 1
i is now 2
i is now 3
i is now 4
>>>
```

   - **The break statement** : The break statement is used to immediately leave the body of its loop. The next statement to be executed is the first one after the body.
 Example: 
 
``` 
 for i in [12, 16, 17, 24, 29]:
    if i % 2 == 1:  # if the number is odd
        break        # immediately exit the loop
    print(i)
print("done")
```
