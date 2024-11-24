# Random-Password-Generator-os-random-
# Password Generator

## Description
This is a **Password Generator** script written in Python. The script allows users to generate customizable passwords of varying lengths. It ensures stronger passwords by introducing random numbers and uppercase letters in the generated strings.

---

## Features
- Generate passwords of user-defined lengths.
- Automatically enforces a minimum length of 3 characters for all passwords.
- Introduces random numeric characters and uppercase letters for added security.
- Supports generating multiple passwords in a single run.

---

## Requirements
This script runs on Python 3.x and requires no external libraries. Make sure you have Python installed on your system.

---

## How to Run
1. Clone or download this repository to your local machine.
2. Open a terminal or command prompt and navigate to the directory containing the script.
3. Run the script using:
   ```bash
   python password_generator.py
   ```
4. Follow the prompts to:
   - Enter the number of passwords you want to generate.
   - Specify the length for each password.
   - View the generated passwords in the output.

---

## Example Usage
### Input:
```
How many passwords do you want to generate? 2
Generating 2 passwords
Minimum length of password should be 3
Enter the length of Password #1: 8
Enter the length of Password #2: 5
```

### Output:
```
Password #1 = a2cDeFgh
Password #2 = b0CdE
```

---

## Script Details

### **Functions**
1. **`generatePassword(pwlength)`**:
   - Generates passwords based on lengths provided as input.
   - Replaces some characters with numbers and uppercase letters to improve password strength.

2. **`replaceWithNumber(pword)`**:
   - Randomly replaces some letters in the first half of the password with numeric characters.

3. **`replaceWithUppercaseLetter(pword)`**:
   - Randomly replaces some letters in the second half of the password with uppercase letters.

4. **`main()`**:
   - Handles user input and displays the generated passwords.

---

## Customization
- Modify the `alphabet` variable to include special characters (e.g., `@`, `#`, `$`, etc.) for more complex passwords.
- Adjust the logic in `replaceWithNumber` and `replaceWithUppercaseLetter` to change how many characters are replaced.

---

## Notes
- The script ensures a minimum password length of 3 characters for security purposes.
- Generated passwords are printed to the console. For production use, consider saving passwords to a file or encrypting them.

---

## License
This project is open-source and free to use for personal or educational purposes.

---

Feel free to adapt the **README** to suit your specific project requirements! Let me know if you need any additional help.
