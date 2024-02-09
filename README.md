# Email-Validation-Program
This Python program validates the format of an email address provided by the user. It ensures that the email adheres to basic requirements such as containing an "@" symbol, having a minimum length, and following certain character conventions.

How It Works--
**Input**: The program prompts the user to enter an email address.
**Validation Criteria:**
The length of the email must be at least 5 characters.
The email must contain exactly one "@" symbol.
The first character of the email must be an alphabetic character.
The email must end with either three or two characters after the last dot.
**Character Checks:**
The program iterates through each character in the email and checks for the following:
Whitespace characters: Each email character is checked for whitespace. If any whitespace is found, the email is considered invalid.
Uppercase alphabetic characters: If any uppercase alphabetic characters are found, the email is considered valid.
Special characters: The program allows the use of "_" (underscore), "." (dot), and "@" (at symbol) in the email. All other special characters are considered invalid.
**Validation Result:**
If the email passes all validation criteria, it is deemed valid.
If any of the criteria are not met, the program prints "Invalid email" along with a message specifying the reason for invalidation.
**Output:** The program provides feedback to the user regarding the validity of the entered email address.
