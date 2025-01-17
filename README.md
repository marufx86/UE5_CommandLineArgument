# UE5_CommandLineArgument

This project demonstrates the use of command-line arguments in Unreal Engine 5 to customize game behavior on startup.

**Functionality**

The project contains a simple scene with a cube. The cube's color can be modified using command-line arguments passed to the packaged executable.

**Usage**

1.  **Package the project:** Package the Unreal Engine 5 project for your target platform (e.g., Windows).

2.  **Run the executable directly (no arguments):** Running the packaged `.exe` file (or its shortcut) without any command-line arguments will display a **white** cube.

3.  **Modify the cube color via command-line arguments:**

    *   To launch the game with a **red cube**, modify the `.exe` file's shortcut:
        *   Right-click the shortcut and select "Properties".
        *   In the "Target" field, append `red` to the existing path. For example:
        
        ```
        C:\Users\user\packges\Windows\cmdLine.exe red
        ```

    *   To launch the game with a **green cube**, use the argument `green` in the same way. For example:

        ```
        C:\Users\user\packges\Windows\cmdLine.exe green
        ```
