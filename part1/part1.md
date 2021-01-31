1.var here is function-scoped and i is declared within the function.
It will display the last value i takes in the loop, which is prices.length. 
2. It will display the last value discountedPrice takes in the loop, 
which is prices[prices.length-1] * (1-discount), since var is function-scoped.
3. The finalPrice will be shown which is equal to the result of 
Math.round(prices[prices.length-1]*(1-discount)*100)/100,
since var is function-scoped.
4. It will return the array discounted = [50, 100, 150]. The for loop
will iterate through the values in discountPrices and the current 
finalPrice will be pushed to discounted. finalPrice is calculated 
by multiplying the current prices value by 1-discount and rounding
to two decimal places. 
5. Since i is declared with let inside the for loop, it is not in the
current scope and ReferenceError that i is not defined is shown.
6. Since discountedPrice is declared with let inside the for loop, it is not in the
current scope and ReferenceError that discountedPrice is not defined is shown.
7. Since finalPrice is declared outside the for loop it is whithin the
scope of the function.The finalPrice will be shown which is equal to the result of 
Math.round(prices[prices.length-1]*(1-discount)*100)/100
8. It will return the array discounted = [50, 100, 150]. The for loop
will iterate through the values in discountPrices and the current 
finalPrice will be pushed to discounted. finalPrice is calculated 
by multiplying the current prices value by 1-discount and rounding
to two decimal places. Since discounted is declared at the start 
of the function, there are no problems with scope.
9.
10.
11.
12.
13. A. student.name
    B. student['Grad Year']
    C. student.function()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[1]
(Not sure if E means first element or index = 1, I assumed second)

14. A. '32' 
2 is converted to char '2' and appended to '3'
    B. 1
char '3' is converted to number 3 and 3-2 is calculated
    C. 3
null is converted to integer 0
    D. '3null'
null is converted to string 'null' and appended to '3'
    E. 4
true is converted to integer 1 and 1+3 is calculated
    F. 0
false and null are both converted to number 0 and added
    G. '3undefined'
undefined is converted to string and appended to "3"
    H. NaN
undefined is numerically converted to NaN. Since "3"
can't be added, error is given as NaN

15. A. true
'2' is converted to number and compared with 1
    B. false
The first char of '12' which is '1' is compared with char '2'
and since it is less than it, false is returned
    C. true
'2' becomes 2 and so returns true
    D. false
strict equality check finds that the values are different
because their types are different
    E. false
true is converted to 1 and is not equal to 2
    F. true
Boolean(2) becomes true and is equal to true, type and all

16. == coverts values to same type while === does not and therefore
only returns true if they are the same type with the same value. 

17.