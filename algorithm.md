---
layout: page
title: Algorithm

---
## Key Algorithms Used

  In my code i use a plethera of Alogorithms most notably in the shapes, to generate these shapes we need to use formulae.

## Number Generation Algorithm

  ![image](https://github.com/user-attachments/assets/26f3b05f-5a65-4806-9263-47c2b12a788f)

  This is my number generation Algorithm.
Algorithm Type: Mersenne Twister (MT19937.
Description: This is a pseudorandom number generator that produces a sequence of numbers with a very long period (2^19937-1) before repeating.

## Rectangle Algorithm

![image](https://github.com/user-attachments/assets/5a42907e-43fe-47b5-9510-bafc9f849fa5)

This is the Rectangle code which includes its Algorith

Algorithm Type: Nested iteratio

Time Complexity: O(width × height) - visits every cell exactly once.

Description: Simple nested loop that fills a rectangular area row by row, column by column.

For the Rectangle what happens is the code fills a grid of width x length with 1s and 0s.

## Triangle Algorithm

![image](https://github.com/user-attachments/assets/894871c8-642b-4443-9578-4efdb7ac741a)

This is my Triangle code which includes its Algorithm.

Algorithm Type: Incremental shape construction.

Description: Uses a mathematical relationship where each row width follows the pattern 2i (where i is the row number).

Purpose: Creates an isosceles triangle with its apex at the top.

Key Formula: Number of characters in row i = 2i.

For the Triangle what happens is :

For each row i (from 0 to height-1):

Prints height - i spaces to center the content (moves progressively left as rows increase).

Prints i * 2 random digits - this is the key formula that creates the triangular shape.

The first row (i=0) has 0 digits.

The second row (i=1) has 2 digits.

The third row (i=2) has 4 digits, and so on.

This creates the expanding width pattern of the triangle.

## Circle Algorithm

![image](https://github.com/user-attachments/assets/60364d00-3830-492a-a7fc-99b13df78a57)

This is my Circle code which includes its Algorithm.

Algorithm Type: Circle equation test.

Description: Uses the algebraic formula for a circle: (x-h)² + (y-k)² ≤ r².

Purpose: Determines whether each point in a rectangular grid falls within a circle.

Efficiency: Scans the entire rectangular area (O(width × height)) but only draws points that satisfy the circle equation.

Mathematical Basis: Euclidean distance calculation from center point.

First we calculate the center point (centerX, centerY) and radius.

It loops through every position in the width x height grid.

For each position (x,y):

    Calculate the distance from center using dx = x-centerX and dy = y-centerY.
    Applies the circle equation: dx² + dy² ≤ radius².
    If the position is inside or on the circle, prints a colored random digit
    If the position is outside the circle, prints empty spaces.
    This creates a circular pattern of digits surrounded by spaces.
    

## Diamond Algorithm 

  ![image](https://github.com/user-attachments/assets/63bca20a-a311-436a-a86f-8253677e5ddd)



This is my Diamond code which includes its Algorithm.

Algorithm Type: Symmetrical shape construction.

Description: Constructs the diamond in two parts - expanding top half and contracting bottom half.

Key Pattern: Uses symmetry to mirror the top half of the diamond for the bottom half.

Mathematical Basis: Linear relationship between row number and row width.

For this Algorithm we reuse the Triangle concept on the top half then reverse it for the bottom half of the Diamond

    










