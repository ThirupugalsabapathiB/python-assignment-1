## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?

    Ans:Python is a general purpose language,and it is broadly applicable across application domain rather than particular application domain.And also python is contrary to domain specific language(DSL).
        python is high level programming language because of easy coding and also to solve different types of problems.

Q2. Why is Python called a dynamically typed language?
    
    Ans:Pyton is a dynamically typed language.basically in normal type the variable do have a type to perform operation using the variable,but in dynamic type the type of variable automatically interprets the type and it can be determined only in the runtime.

Q3. List some pros and cons of Python programming language?

    Ans:Pros:
            1.easy syntax format
            2.versatility
            3.variety of libraries
        Cons:
            1.heavy memory usage
            2.slow speed    

Q4. In what all domains can we use Python?

    Ans: Artificial intelligence
         Machine learning and deep learning
         Used as tool for data scientist
         Database

Q5. What are variable and how can we declare them?

    Ans:A variable is name assigning to an object,whenever we want to use an object we can simply call the variable to access the value stored in it.and it is declare in  variable=10 .

Q6. How can we take an input from the user in Python?

    Ans:The input() fn is used to get user's input.

Q7. What is the default datatype of the value that has been taken as an input using input() function?

    Ans: the default datatype in input() is "string".

Q8. What is type casting?

    Ans:Type casting means changing one data type to another datatype.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

    Ans:yes it can be used
         
         a, b, c = input("Enter the values: ").split(",")
         print("value of a: ", a)
         print("value of b : ", b)
         print("value of c : ", c)
         print()

Q10. What are keywords?

    Ans:Python keywords are special reserved words that have specific meanings and purposes.

Q11. Can we use keywords as a variable? Support your answer with reason.

    Ans:No, we cannot use keywords as a variable.

Q12. What is indentation? What's the use of indentaion in Python?

    Ans:Indentation refers to the spaces in python.it is used to indicate the blocks in the statement.

Q13. How can we throw some output in Python?

    Ans:print() fn.

Q14. What are operators in Python?

    Ans:operators in python are used to perform some operations.

Q15. What is difference between / and // operators?

    Ans:/ is for float division
        // is for integer division

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```

    Ans:print("Inueron"*3)
    
Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

    Ans:
         num = float(input("Enter a number: "))
         if num%2 == 0:
            print("even")
        else:
            print("odd")

Q18. What are boolean operator?

    Ans:True
        False
        And
        Or
        Not

Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```

Q20. What are conditional statements in Python?

    Ans:Conditional statements in python is the condition is stated to be satisfied,if it is satisfied only the execution of program will run,it not satisfied it will not run.

Q21. What is use of 'if', 'elif' and 'else' keywords?

    Ans:"if" is not satisfied elif will execute
        "elif" is not satisfied else will execute
        "else" will execute if and elif fails

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

    Ans:age = int(input("Enter your age: "))
        if age >= 18:
             print("voter")
        else:
             print("Non voter") 

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
`
Ans:
numbers = [12, 75, 150, 180, 145, 525, 50]
add=0
for num in numbers:
  if num%2 == 0:
    add = add+num
  else:
    continue
print(add)

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

Ans:
a, b, c = int(input("Enter three numbers: ")).split(",")
if (a>b) and (a>c):
  print("a is greatest")
elif b>c:
  print("b is greatest")
else:
  print("c is greatest")

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

Ans:
numbers = [12, 75, 150, 180, 145, 525, 50]
lst = []
for num in numbers:
    if num >150:
      if num>500:
       break
    elif num%5==0:
        lst.append(num) 

print(lst)

       output[75,150,145]