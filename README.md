# CODTECH-Task2
Name:PATHLAVATH DIVYA
Company:CODTECH IT SOLUTIONS
ID:CT12PD100
Domain:PYTHON PROGRAMMING
Duration:MAY 20 TO JULY 20
Mentor:SRAVANI GOUNI
Project Overview: Student Grade Tracker in Python
This Python program is designed to help users track and manage student grades. The main functionalities include inputting grades for different subjects or assignments, calculating the average grade, and displaying the overall grade summary, which includes the letter grade and GPA.

###Main Functions and Their Responsibilities
get_letter_grade(average):

Purpose: Determines the letter grade and GPA based on the average grade.
Parameters: average (a float representing the average grade).
Returns: A tuple containing the letter grade (string) and GPA (float).
input_grades():

Purpose: Allows the user to input grades for different subjects.
Returns: A dictionary where the keys are subject names and the values are the corresponding grades.
calculate_average(grades):

Purpose: Calculates the average of the inputted grades.
Parameters: grades (a dictionary with subject names as keys and grades as values).
Returns: A float representing the average grade.
display_summary(grades, average, letter_grade, gpa):

Purpose: Displays a summary of the grades, including each subject's grade, the average grade, the letter grade, and the GPA.
Parameters:
grades (dictionary of subject names and their grades),
average (float average of grades),
letter_grade (string letter grade),
gpa (float GPA).
main():

Purpose: The entry point of the program. Manages the flow of the program from welcoming the user, collecting grades, calculating the average, determining the letter grade and GPA, and displaying the summary.
Program Flow
Welcome Message: The program starts with a welcome message to the user.
Input Grades: The user is prompted to enter grades for various subjects until they type 'done'.
Calculate Average: Once all grades are entered, the program calculates the average grade.
Determine Letter Grade and GPA: The program determines the letter grade and GPA based on the average grade.
Display Summary: Finally, the program displays a summary of the entered grades, the average grade, the letter grade, and the GPA.
No Grades Entered: If no grades are entered, the program informs the user.
##Explanation
The program starts by defining helper functions to perform specific tasks such as getting the letter grade, inputting grades, calculating the average, and displaying the summary.
The main() function orchestrates the workflow, ensuring a smooth interaction with the user from input to output.
The if __name__ == "__main__": block ensures that the main() function runs only when the script is executed directly, not when imported as a module.
This structure makes the program easy to understand, maintain, and extend with additional features if needed.
