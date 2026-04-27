1. Line 12 will print out the length of the input prices array, because the `for` loop stops adding 1 to `i` after it has reached `prices.length`. In this example, it will print 3.

2. Line 13 will print out the last `discountedPrice` value which is the last value of the `prices` array, multiplied by the discount amount, since it is updated in each iteration of the `for` loop. In this example, it will print 150.

3. Line 14 will print out the last `finalPrice` value which is just the same as the last `discountedPrice` value because we multiply with and then divide by 100, and it is updated in each iteration of the `for` loop. In this example, it will print 150.

4. This function will return an array of values that is the same length as the input `prices` array, except that each value in the returned array is equal to the value of the corresponding entry of the `prices` array multiplied with the `discount` value.

5. Line 12 will result in a `ReferenceError` because `i` is now restricted by `let` to the scope of the `for` loop's block, and thus `i` is not defined for line 12 as it is outside the scope.

6. Line 13 will result in a `ReferenceError` because `discountedPrice` is now restricted by `let` to the scope of the `for` loop's block, and thus `discountedPrice` is not defined for line 12 as it is outside the scope.

7. Line 14 will still print out the last `finalPrice` value (150) like before because it is declared at the scope of the function, rather than inside the `for` loop's block, so it is accessible from line 14 which is in the same function.

8. This function will return an array of values that is the same length as the input `prices` array, except that each value in the returned array is equal to the value of the corresponding entry of the `prices` array multiplied with the `discount` value. The use of `let` instead of `var` to declare variables doesn't change the function from before.

9. Line 11 will result in a `ReferenceError` because `i` is now restricted by `let` to the scope of the `for` loop's block, and thus `i` is not defined for line 12 as it is outside the scope.

10. Line 12 will print out the length of the input `prices` array, which is a `const` now but that doesn't make a difference since it doesn't change. In this example it prints out 3.

11. This function will return an array of values that is the same length as the input `prices` array, except that each value in the returned array is equal to the value of the corresponding entry of the `prices` array multiplied with the `discount` value. It doesn't change because `discounted` is a `const` since the array's contents can still be modified, just that the variable cannot be reassigned.

12. A. `student.name`
    B. `student['Grad Year']`
    C. `student.greeting()`
    D. `student['Favorite Teacher'].name`
    E. `student.courseLoad[0]`

13. A. The output is '32' since it takes the + to involve string conversion so it appends.

    B. The output is 1 since the - sign makes it do numeric subtraction.

    C. The output is 3 since null is taken to be 0 under numeric type conversion from the number 3.

    G. The output is '3null' since it interprets + as involving string conversion so it's appending string null to '3'.

    E. The output is 4 since boolean true is taken to be 1 under numeric conversion.

    F. The output is 0 since both values are taken to be 0 under numeric conversion.

    G. The output is '3undefined' since it interprets + as string conversion so it's appending string undefined to '3'.

    H. The output is NaN since undefined is interpreted as NaN under numeric conversion and any arithmetic with NaN results in NaN.

14. A. Returns true since numeric conversion treats '2' as the number 2 which is greater than 1.

    B. Returns false since the first char of '12' is one and 1 < 2

    C. Returns true since both are same under numeric conversion.

    D. Returns false because it fails the strict equality check as they're of different types.

    E. Returns false since true turns into 1 != 2 under numeric conversion.

    F. Returns true because forcing conversion of `Boolean(2)` which is done before the comparison makes it true since it's not zero so they become equal.

15. `==` checks equality with type conversion, while `===` is strict so it checks equality without type conversion.