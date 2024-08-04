Name: JENIFER CATHERINE D

Company: CODTECH IT SOLUTIONS

ID: CT08DS4048

Domain: Cyber security and Ethical Hacking

Duration: JULY to AUGUST 2024

Mentor: Neela Santhosh Kumar

Overview of the Project

Project: PASSWORD STRENGTH CHECKER


Objective

The provided Java code is a simple password strength checker. Here's an overview of its functionality

Key Activities

1. Class Declaration:

   - The class is named PasswordStrengthChecker.

2. CheckPasswordStrength Method:
   - This static method takes a String parameter named password and evaluates its strength.
   - A score variable is initialized to 0.
   - The method then checks for various criteria to increment the score:
     - Password length of at least 8 characters.
     - Presence of uppercase letters.
     - Presence of lowercase letters.
     - Presence of digits.
     - Presence of special characters (e.g., !@#$%^&*(),.?":{}|<>).
   - Based on the score (0 to 5), it returns a corresponding strength description:
     - 5: "Very Strong"
     - 4: "Strong"
     - 3: "Medium"
     - 2: "Weak"
     - 0-1: "Very Weak"

3. Main Method:
   - The main method serves as the entry point of the program.
   - It uses a Scanner to read a password input from the user.
   - It calls checkPasswordStrength to determine the password's strength.
   - The result is printed to the console.
   - Finally, the scanner is closed to free resources.
