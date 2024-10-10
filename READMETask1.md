NAME : GAURAV S
COMPANY : CODTECH IT SOLUTIONS
ID : CT08DS8838
DOMAIN : PYTHON PROGRAMMING
DURATION : OCT - NOV 2024
MENTOR : - (NOT MENTIONED IN OFFER LETTER)

![Screenshot 2024-10-11 011728](https://github.com/user-attachments/assets/f7904edf-5d8a-48b6-9bfc-71c67160e0e1)


Overview of the tkinter-based GUI Calculator

Objectives:

Create a graphical calculator that operates similarly to a basic desktop calculator.
Use a separate window (GUI) for the calculator interface, allowing users to interact with buttons like on a physical calculator.
Perform basic arithmetic operations such as addition, subtraction, multiplication, and division.
Handle errors gracefully, such as division by zero or invalid input.

Key Features:

Graphical User Interface (GUI):

The calculator opens in a separate window, similar to traditional PC calculators.
Users can input numbers and operators via clickable buttons, which are displayed in a text entry box.

Basic Arithmetic Operations:

Supports addition (+), subtraction (-), multiplication (*), and division (/).      
Users can clear the input with the "C" button.
The "=" button evaluates the entered expression and displays the result.



Error Handling:

Handles division by zero with a pop-up error message.
Catches invalid inputs, such as incomplete expressions or unsupported operations.

Responsive Design:

Buttons are organized in a grid format, with responsive sizing to create a clean, simple layout.
Numeric buttons (0-9) and operators (+, -, *, /) are laid out intuitively for ease of use.

Real-time Display:

As the user clicks on buttons, the input is displayed in a text field.
The display is updated with each button press, and the result is shown after pressing "=".

Technologies Used:

tkinter library:

Provides the tools to create the window, buttons, and input display.
Handles the layout of components using the grid system.
Manages events, such as button clicks, through callback functions.

eval() function:

Evaluates mathematical expressions entered by the user.
It simplifies parsing the user's input, allowing for dynamic calculations.

Error handling mechanisms:

Use of try-except blocks to catch exceptions like division by zero or invalid syntax.
messagebox from tkinter is used to alert users about errors.
