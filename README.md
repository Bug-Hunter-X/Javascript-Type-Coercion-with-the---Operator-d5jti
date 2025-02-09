# Javascript Type Coercion Bug
This example demonstrates a common Javascript bug related to type coercion with the + operator.
When adding a number and a string, Javascript converts the number to a string and performs string concatenation instead of numerical addition. This can lead to unexpected results if not carefully handled.

## Bug
The `foo` function is supposed to add two numbers. However, when one of the arguments is a string, the + operator performs string concatenation.  The solution shows how to handle this by explicitly converting to numbers.

## Solution
The solution uses the `Number()` function to convert the arguments to numbers before performing the addition. This ensures that the function behaves as intended regardless of the input types.
