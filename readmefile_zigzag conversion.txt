🚀 Approach

This solution simulates the zigzag traversal:

Create a list of strings for each row
Traverse the input string character by character
Move downwards and then upwards diagonally
Append characters to respective rows
Finally, join all rows to get the result
🧠 Key Logic
Use a variable current_row to track position
Use a boolean going_down to control direction
Reverse direction when reaching:
Top row (0)
Bottom row (numRows - 1)