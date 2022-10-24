Part 2
1. “3” will be printed. We have looped through 0 to 2 and now are out of the bounds for the for loop to execute. However, since i is declared with the var keyword, it is not scoped to only the for loop, but can be seen anywhere in the function.
2. “150” will be printed, since this is the discounted price of last item and is a var, which can be seen anywhere within the function.
3. “150” will be printed again, since this is the final price after the discount of the last item and is a var, which can be seen anywhere within the function.
4. The function will return [50, 100, 150] since it is working to provide a 50% discount on all the items, and is able to do this successfully since it can access all the var variables throughout the entire function.
5. The code causes an error. Since i is declared with the let keyword inside the heading of the for loop, it cannot be seen outside of the for loop.
6. The code causes an error. discountedPrice cannot be seen outside of the for loop since declaring the variable with the let keyword limits its scope to only that loop. 
7. “150” will be printed, since that’s the last discounted price to be calculated, and the variable has the scope of the whole function because it was declared with the let keyword inside the function but outside the for loop.
8. The function will return [50, 100, 150] since it is again working to provide a 50% discount on all the items, and is able to do this successfully since it can access all the let variables as needed (all of the variables needed outside of the loop are declared outside of the loop).
9. Same as question 5: the code causes an error. Since i is declared with the let keyword inside the heading of the for loop, it cannot be seen outside of the for loop.
10. “3” will be printed. This is because this is the length of the array passed as a parameter in the discountPrices function call.
11. The function will return [50, 100, 150]. This is because, while declaring the discounted array as a constant means we cannot reassign it, we are allowed to add to the array using the push method. Therefore, we can successfully push the discounted prices to the array.
12.     
    a. student.name  
    b. student[‘Grad Year’]  
    c. student.greeting()  
    d. student[‘Favorite Teacher’].name  
    e. student.courseLoad[0]  
13.    
    a. 32, since the left operand being a string means the + operator will convert the right operand to a string and perform string concatenation  
    b. 1, since the - operator converts the string ‘3’ to a number  
    c. 3, since null is converted to 0  
    d. 3null, since null is converted to the string ‘null’  
    e. 4, since true is converted to 1  
    f. 0, since both operands are converted to 0 in computations  
    g. 3undefined, since undefined is converted to the string ‘undefined’  
    h. NaN, since undefined is converted to NaN  
14.    
    a. True, since 2 is converted to a number  
    b. False, since they are compared as strings ‘2’ and ’12’, and the first character of 12 being 1 means 12 comes first in lexicographical order  
    c. True, ‘2’ is converted to 2  
    d. False, the operands are not the same type  
    e. False, true is converted to 1  
    f. True, the boolean value of 2 is true, and then the operands are of the same type   
15. == is an equality check, where variables of different types will just be converted to numbers to be compared. However, === is a strict equality check, which means that it accounts for type too. === will first check if the two operands are of the same type, and if not, it will return false. If they are of the same type, it then checks whether they are equal or not.
16. See part2-question16.js
17. The result will be [2,4,6] since the modifyArray function is passed doSomething as a parameter. The modifyArray function then calls doSomething on each element of the array, and doSomething multiplies each element by 2.
18. See part2-question18.js
19. The code prints 1, then 4, then 3, and finally 2. This is because 1 is printed first with no delay, and then 4 is printed after also with no delay. Then, 3 prints next since it is in a setTimeout function (even though the delay is set to 0), and 4 is printed last because it has a longer delay of an entire second.
