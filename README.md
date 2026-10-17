
KIZITO NJANG MBABIT
COURSE: 1AH-Fall 2026-Computer Science I SWCP

Project purpose
This C++ program processes the coordinate data supplied in “M08 Final Project InputData.docx” and prints the characters on a two dimensional grid. The printed grid is intended to display the block annotated pattern from the assignment.
Input data
Each input record contains three fields: x-coordinate, character (█ or ░), and y-coordinate. The program includes the supplied records in a multiline string so it can run in an online C++ compiler without needing to upload a separate data file.
Program algorithm
1.	Parse each x-coordinate, character, and y-coordinate into a Point record.
2.	Find the maximum x and y coordinates in the input.
3.	Create a two dimensional grid with maxY + 1 rows and maxX + 1 columns, initialized with spaces.
4.	Place each input character at grid[y][x].
5.	Print the grid one row at a time so the pattern can be viewed.
How to compile and run
Open M08_Final_Project.cpp in a C++17-compatible compiler (for example, Programiz or Visual Studio Code), run the program, and inspect the output panel. Use a monospaced font and a wide output panel to preserve the grid alignment.
Expected output and verification
The program prints “REVEALED OUTPUT,” followed by the coordinate grid. The heading is only a label; the grid itself is the result. Verify the displayed pattern against the assignment example or ask the instructor if the rendered pattern does not reveal a recognizable answer. Successful compilation by itself does not prove that the decoded pattern is correct.
Files included
•	M08 Final Project.cpp complete C++ source code with the supplied input data.
•	Program Output.txt   text output from a local test run.
•	Flowchart.png flowchart of the program logic.
•	UML Diagram.png  UML-style diagram of the Point structure and main processing flow.
