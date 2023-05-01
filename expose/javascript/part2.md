#Part2
1. 3 will be printed, since i is still defined in the function scope due to the var keyword.
2. 150 will be printed, since in the last iteration of the for loop discountedPrice is assigned to 150, and it is still accessible in the funtion scope after the loop.
3. 150 will be printed, same reasoning as question 2.
4. It will return an array that contains corresponding discounted prices of prices provided, since we used a for loop to apply the discount on each price and pushed the discounted pricse to the discounted array.
5. Error. Since i is defined with the let keyword, i is out of scope outside of the for loop, so the program throws an error when we try to access it.
6. Error. Same reasoning as 5., discountedPrice is out of scope outside the for loop.
7. 150 will be printed, finalPrice is defined in the same scope where console.log is called.
8. It will return an array that contains corresponding discounted prices of prices provided, since we used a for loop to apply the discount on each price and pushed the discounted pricse to the discounted array.
9. Error, since i is defined using the let keyword, is it out of scope when the console.log is called.
10. 3 is printed. In javascript, array is essentially an object under the hood, so length is an attribute of an object. It is updated internally when user modify (in this case, push) an existing array. 
11. An array with discounted prices, same reasoning as 8.
12. A. student.name B. student['Grad Year'] C. student.greeting(); D.student['Favorite Teacher'].name E. student.courseLoad[0]
13. A.  "32", + concatenate strings. B. 1, 3 is cast to number. C. 3, null evaluates to 0. D. "3null", + concatenate. E. 4, true,  evalueted as 1. F. 0, false and null both evalutes to 0. G. "3undefined", undefined is evaluated as a string and concatenated. H. NaN, - only works when both sides are numbers, undefined cannot be cast to a number.