## Part 1a


### var declaration

1. values added: 20
2. final result: 20

### let declaration

1. values added: 20
2. we will get an error because using 'let' only allows the variable result to be accessed in the block it was declared in

### const declaration

1. we will get an error because after a const variable is declared, we cannot modify it
2. we will get an error here as well because the error from line 9 hasn't been fixed


## Part 1b

1. 3 will be logged to the console because that is the last value of i that we get. 3 sets the for loop condition to false. also since it was declared using var we can access it.
2. 150 will be logged to console because it is the calculated value of the last item in the list for discountPrice. it was declared using var so we can access it.
3. 50 will be logged to console because it is the calculated value of the last item in the list for finalPrice. it was declared using var so we can access it.
4. the discounted array that holds the final prices will be returned. this is because we used var to declare it so we can access it anywhere within the program. 
5. we will get an error saying that i is not defined. this is because we used let to declare i, which does not allow it to be accessed outside the loop
6. we will get an error because we used let to declare discountedPrices, which does not allow it to be accessed outside the loop
7. 150 is logged to the console because finalPrice was declared with let in the function and we also try to access it within the function so it is in the same scope
8. the discounted array that holds the final prices will be returned because when we return it, it is still in the function, so it is in the scope that the declaration let allows
9. we will get an error saying that i is not defined. this is because we used let to declare i, which does not allow it to be accessed outside the loop
10. 3 will be logged to the console. The variable length was declared using const and it hasn't been modified so it is valid and can be accessed. 
11. The function will return the discounted array with the discounted prices. This works because we are modifying the values in the list, but we are not changing what discount is referring to.
12. Notation
    a. student.name
    b. student["Grad Year"]
    c. student.greeting()
    d. student.["Favorite Teacher"].name
    e. student.courseLoad[0]

13. Arithmetics
    a. 32 because integers map to the string representation
    b. 1 because we are using - (minus) so 3 will be treated as an integer
    c. 3 because null doesn't add anything to 3
    d. 3null because 3 is a string so null will be represented as a string
    e. 4 because true has the value 1
    f. 0 because false has the value 0 and adding null doesn't add anything to 0
    g. 3undefined because 3 is a string so undefined will be represented as a string as well
    h. NaN because this behavior is undefined

14. Comparison  
    a. true because 2 will be seen as an integer, and 2 is greater than 1
    b. false because this compares two strings, which checks the alphabetical order. 1 is smaller than 2 in terms of alphabetical order
    c. true because it is a regular equality check which can do type conversion
    d. false because a strict equality check does not do type conversions. for it to be true the type must be the same as well
    e. false because true has the value 1, which is not equal to 2
    f. true because Boolean(2) gives us true. 2 is not 0 or any other value that would give us a value of false

15. a regular equality check (==) can do type conversions to numbers. a strict equality check (===) will not do the type conversion, so if the types are different it will automatically be false

17. an empty newArr is created. then we populate newArr with values that have been doubled from doSomething. in each iteration of the for loop, we go to doSomething and multiply the value in that index by 2. so the result is we get newArr = [2,4,6]

19. the console will log 1. then 4 will be logged to the console. next, the timer will be set. Since at line 4 the timer was set at 0, the next number to be logged to console is 3. One second later 2 will be logged to console




