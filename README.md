# C++ 3-Screen Window Setup

This json provides a build method for C++ programming:

- **User Input:** Use the `input.txt` file to provide input to your program.
- **Program Output:** The output of your program will be written to the `output.txt` file.
- **Source Code:** Write your C++ code in the appropriate source file.

## Setting Up tasks.json

Depending on your operating system, copy the appropriate file:

- **Windows:** Copy the contents of `#file:win_tasks.json`.
- **Mac:** Copy the contents of `#file:mac_tasks.json`.

### Steps to Generate `tasks.json` in VS Code

1. Open your project folder in Visual Studio Code.
2. Press `Ctrl+Shift+P` (or `Cmd+Shift+P` on Mac) to open the Command Palette.
3. Type `Tasks: Configure Task` and select it.
4. Choose `Create tasks.json file from template` (if prompted).
5. Replace the contents of the generated `.vscode/tasks.json` file with the contents from the appropriate file above.

## Running the Code

- Makesure before doing the build proccess the program file should be selected if the cursor on another file the build proccess gives an error.

- To build and run your code, press `Ctrl+Shift+B` in Visual Studio Code.


This setup helps you easily manage input and output files while developing.
