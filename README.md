# question-3024
Solution to the question no 3024 on leet code 

3024. Type of Triangle

You are given a 0-indexed integer array nums of size 3 which can form the sides of a triangle.

A triangle is called equilateral if it has all sides of equal length.
A triangle is called isosceles if it has exactly two sides of equal length.
A triangle is called scalene if all its sides are of different lengths.
Return a string representing the type of triangle that can be formed or "none" if it cannot form a triangle.

This Java method triangleType determines the type of triangle based on the lengths of its three sides:

Sort the sides to make comparison easier.

Check for triangle validity: If the sum of the two smaller sides is not greater than the largest side, it’s not a triangle ("none").

Check if all sides are equal: If yes, it's an "equilateral" triangle.

Check if any two sides are equal: If yes, it's an "isosceles" triangle.

Else, all sides are different, so it's a "scalene" triangle.

In short:

Invalid → "none"

3 equal sides → "equilateral"

2 equal sides → "isosceles"

All sides different → "scalene"
