1. Line 12 will print "3"; because i was defined in the for loop with keyword var, thus making it accessible inside the entire function, including line 12.
2. Line 13 will print "150"; because in the final iteration of the for loop, it uses the last entry in prices and applies the discount: discountedPrice = 300 * 0.5 = 150.
3. Line 14 will print "150"; as state before, discountedPrice = 150, so finalPrice = (150 * 100) / 100 = 150.
4. This function will return the array {50, 100, 150}; because in the for loop, the processes described in questions 2-3 will be applied to all entries in the input array, and then pushed to the discounted array.
5. This code will cause an error; because this time, i was defined with the let keyword, the print line was outside the scope of the for loop, thus giving an error.
6. This code will cause an error; with the same reason as question 5, discountedPrice was defined with let inside the for loop.
7. Line 14 will print "150"; because finalPrice was defined in the same function as the print line, and the same process was applied as question 3.
8. This function will return the array {50, 100, 150}; for the same reasons as question 4 (there are no scope errors without the print lines).
9. This code will cause an error; for the same reason as question 1: i was defined with the let keyword.
10. Line 12 will print "3"; because the length of the input array is 3 and the length variable is constant.
11. This function will return the array {50, 100, 150}; because the for loop resets on each iteration, redeclaring discountedPrice on each iteration, not causing an error.
12. notations:
    1. student.name
    2. student['Grad Year']
    3. student.greeting()
    4. student['Favorite Teacher'].name
    5. student.courseLoad[0];
