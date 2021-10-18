**Q1.** Line 12 will print the number 3. This is because the input price array was of size 3 so the for loop ran till i variable became 3.

**Q2.** Line 13 will print the number 150. This is because the last price in the array was 300 and the discount was 0.5 which made the discountedPrice 150.

**Q3.** Line 14 will also print the number 150. This is because the calculations made to the discountedPrice gives 150 as result.

**Q4.** The function returns an array with 3 elements [50, 100, 150]. 
    All of the finalPrice (calculted with discountedPrice) are added to the discounted array through the for loop and this array is returned by the function. 

**Q5.** Line 12 throws an error, 'i is not defined'. This is because line 12 is trying to access a let variable outside its scope. i is a let variable defined in the for loop so its scope is limited to the for loop block and cannt be used outside it.

**Q6.** Line 13 throws an error, 'discountedPrice is not defined'. This is because line 13 is trying to access a let variable outside its scope. discountedPrice is a let variable defined in the for loop so its scope is limited to the for loop block and cannt be used outside it.

**Q7.** Line 14 will print the number 150. This is because the calculations made to the discountedPrice gives 150 as result. Also, the scope of finalPrice is the function block which means line 14 is accessing this let variable inside its scope and there will be no error.

**Q8.** The function returns an array with 3 elements [50, 100, 150]. 
    All of the finalPrice (calculted with discountedPrice) are added to the discounted array through the for loop and this array is returned by the function. 
    
**Q9.** Line 11 throws an error, 'i is not defined'. This is because line 11 is trying to access a let variable outside its scope. i is a let variable defined in the for loop so its scope is limited to the for loop block and cannt be used outside it.

**Q10.** Line 12 will print the number 3. This is because length variable is a constant whose value is the length of the price array which is 3. 

**Q11.** The function returns an array with 3 elements [50, 100, 150]. 
    All of the discountedPrice(s) are calculated and added to the discounted array through the for loop and this array is returned by the function.

**Q12.**
    A. student.name
    B. student['Grad year']
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]
  
**Q13.** 
    A. '32' since integers map to thier exact string representation for addition and plus sign for strings result in concatenation.
    B. 1 since string map to thier exact integer representation for subtraction.
    C. 3 since null object maps to 0 and 0+3=3.
    D. '3null' since null object map to thier exact string representation and the plus sign will result in concatenation.
    E. 4 since true maps to 1 and 1+3=4.
    F. 0 since both false and null map to 0 the result will be 0.
    G. '3undefined' since integers maps to thier exact string representation for addition and plus sign will result in concatenation.
    H. NaN since undefined maps to NaN and subtracting a number from NaN will result in NaN.

**Q14.**
    A. true since here string '2' maps to integer 2 and 2 is greater than 1.
    B. false since strings are compared lexicographically and therefore '2' is greater than '1'.
    C. true since here string '2' maps to integer 2 and its equal.
    D. false since thier datatypes are different (one is integer and other is string).
    E. false since true maps to 1 and 1 is not equal to 2.
    F. true since they are both of the same datatype and true.

**Q15.** 
- == compares 2 variables while ignoring the data types. It will convert one of the operands if they are not of the same type and then perform the comparision.
- === compares 2 variables but also checks the data types. It checks the datatype first and if they are not the same, it returns false and doesnt even compare the operands.

**Q16.** code in part2-question16.js file

**Q17.** Calling the function will return an array with the values [2, 4, 6]. 

Inside the for loop, 
- we call the function doSomething which is taking a value and multiplying it by 2.
- then we add the returned value from doSomething function to the new array. 

We we put the parameters in we know the length of array is 3 so the loop will run 3 times. In each iteration of the loop, we take an integer from the array, doble it using the doSomething function and add this new doubled value to the new array.
The new array will have doubled values of the original array values.

**Q18.**

**Q19.** The output of the code is:
1
4
3
2





