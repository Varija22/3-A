PROGRAM 1
Aim:
To write a C++ program that checks whether a given number is positive, negative, or zero.

Tools Used:

Programiz (Online C++ compiler)

Visual Studio Code (with C++ extension and GCC compiler)

Theory:
In C++, conditional statements like if, else if, and else are used to make decisions based on conditions. A number is said to be:

Positive if it is greater than 0

Negative if it is less than 0

Zero if it is exactly 0

Using a single if-else ladder, we can compare the input number and display the appropriate category.

Algorithm:

1.Start the program.

2.Declare an integer variable.

3.Prompt the user to enter a number.

4.Use cin to read the input.

5.Use if-else conditions to check:

6.If the number is greater than 0, display "Positive"

7.If less than 0, display "Negative"

Else, display "Zero"

8.End the program.

Conclusion:
The program was successfully written and executed. It determines whether an entered integer is positive, negative, or zero using conditional logic in C++


PROGRAM 2
Aim: To write a C++ program that takes marks of five subjects, calculates the average, and displays the corresponding grade based on the average.

Tools Used:

Programiz (Online C++ compiler)

Visual Studio Code (with C++ extension and GCC compiler)

Theory: This program takes marks from five subjects as input. The average is calculated by summing all marks and dividing by 5. Based on the average, grades are assigned using an if-else ladder. Input validation is also included to ensure the average lies between 0 and 100.

Grading logic used:

90–100 → O Grade

80–89 → A+ Grade

70–79 → A Grade

60–69 → B Grade

50–59 → C Grade

Below 50 → FAIL

Algorithm:

1.Start the program.

2.Declare variables to store marks for five subjects.

3.Take user input for all five marks.

4.Calculate the average using integer division.

5.Use a series of if-else conditions to determine the grade:

6.If average is between 90–100 → O

7.If between 80–89 → A+

8.If between 70–79 → A

9.If between 60–69 → B

10.If between 50–59 → C

11.If below 50 → FAIL

12.Handle invalid averages outside 0–100 with an error message.

13.Display the result.

14.End the program.

Conclusion: The program was successfully implemented to calculate the average of five subject marks and assign the appropriate grade. It demonstrates the use of arithmetic operations, conditional logic, and input-output handling in C++.


PROGRAM 2
Aim:
To write a C++ program that takes the coordinates of a point (x, y) and determines whether the point lies in a specific quadrant, on the X-axis, Y-axis, or at the origin.

Tools Used:
Programiz 
Visual Studio Code 
Theory:
In the Cartesian coordinate system, the location of a point is determined using two values: the x-coordinate (horizontal) and the y-coordinate (vertical). The position of a point can fall into one of the four quadrants, on the X or Y axis, or at the origin.

1st Quadrant: x > 0, y > 0

2nd Quadrant: x < 0, y > 0

3rd Quadrant: x < 0, y < 0

4th Quadrant: x > 0, y < 0

X-axis: y = 0 and x ≠ 0

Y-axis: x = 0 and y ≠ 0

Origin: x = 0 and y = 0

Algorithm:

1.Start the program.

2.Declare two integer variables for x and y coordinates.

3.Take user input for x and y.

4.Use if-else conditions to check the location:

5.If both x and y are 0 → Origin

6.If x > 0 and y > 0 → 1st Quadrant

7.If x < 0 and y > 0 → 2nd Quadrant

8.If x < 0 and y < 0 → 3rd Quadrant

9.If x > 0 and y < 0 → 4th Quadrant

10.If x = 0 and y ≠ 0 → Y-axis

11.If y = 0 and x ≠ 0 → X-axis

12.Display the result.

13.End the program.

Conclusion:
The program was successfully executed to determine the location of a point in the 2D coordinate plane. It uses conditional logic to handle all possible positions of the point based on user input.

