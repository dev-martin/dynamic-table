# dynamic-table
Dynamic HTML table with JavaScript

1. Get user inputs using the Javascript prompt function. User will be prompted multiple times to enter input
values where each time the user will enter one input.

2. The table header row should have 3 columns: "Count", "Value", and "Cubed Value".

3. The table data rows should also have 3 columns:

The first column should display which valid input iteration that value corresponds to. The count for
valid input steps should start with 1.

The second column should be the value you entered, and

The third column should be the cube of that number.

4. Additionally, your script should keep a running tally of the sum of all the values entered and display that in
the last row of the table with the column: "the sum of all values entered" in the first cell, and the sum in the
second cell. The third cell should be blank.

5. The only styling you need to apply is a border with a value of 10. You can add this to the opening table
tag.

6. If you enter a value that is not a number your program should respond with an Alert box to the user letting
them know that the value they entered is not valid. Any invalid input should not count as an iteration step
in your table.

7. Your program should terminate execution/prompting the user for values when the user enters "done".

8. If user enters "Cancel", do not display any output -- i.e., no table will be displayed

9. If the first input is "done", display the title, and the table with the header row and the last row showing the
running tally (0) for this case.

10. Lastly, for any non-integer values entered, your program should display them inside the table with the
nearest integer value. For example, if you enter 5.49999, your program should return the value of 5.
However, if you enter 5.5 your program should return a value of 6.
