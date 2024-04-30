1. The console will print the value of i, which will be prices.length = 3, since the var identifier makes it accessible throughout the whole function.
2. The console will print 150, since the last value to discount is 300, and a 50% discount would be 150.
3. The console will print 150, since the last value to discount is 300, and a 50% discount would be 150, and the finalPrice after rounding is the same.
4. The console will return [ 50, 100, 150 ], since all of the prices will have their discounts calculated.
5. Error; Since the keyword let will cause the i to only be accessible in the for loop, the console.log statement will not be able to access it.
6. Error; Since the keyword let will cause the discountedPricde to only be accessible in the for loop, the console.log statement will not be able to access it.
7. The console will print 150 since final price was defined in the scope of the function.
8. The function will return [ 50, 100, 150 ] since each price is already discounted and accessible since the array discounted was defined in the scope of the function.
9. Error; The let keyword keeps the console.log from getting the value of i, which is contained in the for loop.
10. The console will print 3 since length is defined in the scope of the function.
11. The function will return [ 50, 100, 150 ] since discounted can still have items added to it.
12. 
    A: student.name
    B: student["Grad Year"]
    C: student.greeting()
    D: student["Favorite Teacher"].name
    E: student.courseLoad[0]
13. 
    A: '32'; since the 2 is casted into a string and concatenated with 3
    B: 1; since the 3 is turned into a number
    C: 3; since null is basically nothing
    D: '3null'; since null is casted into a string
    E: 4; since true is converted to 1
    F: 0; since false is 0 and null doesn't add anything
    G: '3undefined' since undefined turns into a string
    H: NaN; since you can't take away undefined from 3 numerically
14.
    A: True; 2 is converted to a number and 2>1
    B: False; char value of 2 is less than 12's
    C: True; converting the 2 to a number makes them the same
    D: False; they are not of the same type
    E: False; true is 1
    F: True; any boolean conversion of a non-zero is true
15. == will automatically convert type when checking, while === checks if value and type are the same.
16. in the js file
17. The loop will run for as many items there are in the array that is passed, which is 3. For each of these items, the item will be doubled by the doSomething function, making all of the items in the newArr array double the original item from array.
18. in the js file
19. 1 4 3 2, separated by newlines.