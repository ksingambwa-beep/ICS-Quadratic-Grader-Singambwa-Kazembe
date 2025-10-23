# ICS-Quadratic-Grader--Singambwa-Kazembe-
Improved Grading System and Quadratic Equation Solver
            ICS-Quadratic-Grader
This is a single-page web application created for the ICT251 Web Technologies assignment.

    Description
This project contains two simple utilities in one index.html file:
1.	Quadratic Equation Solver: Solves equations of the form ax^2 + bx + c = 0. It calculates the discriminant, determines the nature of the    roots (real, repeated, or complex), and displays the roots.
2.	Grading System: Converts a numeric score (from 0 to 100) into a letter grade based on the ICT251 grading scale.

    How to Run
Since this is a single, self-contained HTML file, there is no server required.
1.	Clone or download this repository.
2.	Find the index.html file.
3.	Double-click the index.html file to open it in your preferred web browser (e.g., Chrome, Firefox, Edge).
4.	Use the forms to perform calculations.

Test Cases
|  a  |  b  |  c  | Discriminant |            Nature           |               Roots                |
|-----|-----|-----|--------------|-----------------------------|------------------------------------|
|  1  | -5  |  6  |      1       |   Two distinct real roots   |         x = 3  or  x = 2           |
|  1  |  2  |  1  |      0       |    One real repeated root   |               x = -1               |
|  1  |  2  |  5  |     -16      | Two complex conjugate roots |    x = -1 + 2i  or  x = -1 - 2i    |
|  2  |  0  | -8  |      64      |   Two distinct real roots   |         x = 2  or  x = -2          |
|  1  | abc |  3  |      -       | Error: 'b' must be a number |                 -                  |

Quadratic Solver
|  Score    |   Expected Grade   |
|-----------|--------------------|
| 100 - 85  |       A+           |
|  84 - 75  |       A            |
|  74 - 65  |       B+           |
|  64 - 60  |       B            |
|  59 - 55  |       C+           |
|  54 - 50  |       C            |
|  49 - 0   |       D            |
|     - 5   |     Error          |
|    101    |     Error          |
|    abc    |     Error          |
