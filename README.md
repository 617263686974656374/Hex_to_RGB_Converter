# Hex_to_RGB_Converter
This tool is straightforward and user-friendly, designed to make color conversions as easy as possible. Happy coloring!

This Java program is designed to convert hexadecimal color codes into their corresponding RGB (Red, Green, Blue) values. It's a simple yet effective tool for anyone working with colors in digital formats, especially useful for web developers, graphic designers, and anyone interested in color theory.

**Functionality:**

- The program prompts the user to input a hexadecimal color code (e.g., `#FFFFFF`).
- It expects a 6-character hexadecimal string (without the `#` symbol).
- The program then converts this hex code into RGB values.
- If the user inputs an invalid hexadecimal string (not 6 characters) or a string with characters outside the hexadecimal range (0-9, A-F), it prompts the user to re-enter the hex code.
- Additionally, the program checks for negative RGB values, which are invalid, and prompts for re-entry if found.

**Usage:**

1. Run the program.
2. When prompted, enter the hexadecimal color code (6 characters, e.g., `FFFFFF`).
3. The program will display the corresponding RGB values in the format `rgb(red,green,blue)`.

**Error Handling:**

- The program includes error handling to manage incorrect inputs:
  - If the input is not exactly 6 characters.
  - If the input includes non-hexadecimal characters.
  - If the resulting RGB values are negative.
- In any of these cases, the user is prompted to re-enter a valid hexadecimal string.

**Example:**

- Input: `FFFFFF`
- Output: `rgb(255,255,255)`
