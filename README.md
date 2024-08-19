# 5.1 Check Mail

## Java Documentation
[Control Flow](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/flow.html)

## Java Tutorial
[Control Flow](https://runestone.academy/ns/books/published/apcsareview/Conditionals/toctree.html)
## Background:
The U.S. post office has rules about mailing packages. A package cannot be mailed first class if the
sum of its length and girth is greater than 100 inches, or if the package weighs more than 70 pounds.
The girth is the perimeter around the height and width, where the length is defined as the longest of
the three dimensions.
## Assignment:
Write a program that takes in the weight of the package and the three dimensions of the package in
any order. The program should determine the longest dimension of the package, calculate the girth,
and compute the size of the box. The program should then print out one of the following messages
about this package:
1. Package is too large and too heavy.
2. Package is too large.
3. Package is too heavy.
4. Package is acceptable.

Let’s look at how to design this class.

Stepwise refinement 1 - Overall sections of this problem:

- Get data from user
- Solve math
- Print answer

Stepwise refinement 2 - More detailed pseudocode version:

- Prompt user for three dimensions
- Prompt user for weight
- Determine longest of three dimensions
- Calculate the girth using the other two dimensions.
If the package is too big and too heavy, print appropriate message else if package is too big, print appropriate message else if package is too heavy, print appropriate message else print package is acceptable

Stepwise refinement 3 - Determining longest of three dimensions:
- Use three variables, called dim1, dim2, and dim3. Try to end up with dim1 holding the largest value.
- Compare dim2 and dim1, if dim2 is greater, swap dim1 and dim2, dim1 will be holding largest value.
- Compare dim3 and dim1, if dim3 is greater, swap dim1 and dim3, dim1 is still holding largest value.
- Dim1 has largest value, compute math for package
