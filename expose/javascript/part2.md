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