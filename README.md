ASCII Art Generator

This project is a C++ program that generates ASCII art based on shapes defined in a configuration file. It allows you to create figures such as rectangles, circles, lines, points, and place light sources on a canvas.

Implemented Features:

Drawing points at specified coordinates.
Drawing lines with specified start and end points.
Drawing rectangles with specified coordinates, width, height, and symbol.
Drawing circles with specified center coordinates, radius, and symbol.
Placing light sources at specified coordinates.
How to Use:

Prepare a configuration file (e.g., config.txt) with the following format:

The first line should contain the canvas width and height (e.g., "20 10" for a 20x10 canvas).
The second line should specify the output file name (e.g., "output.txt").
The third line should specify the symbol for empty pixels (e.g., ".").
After that, you can define the shapes you want to draw and light sources, one per line, using the following formats:

Point: "Point x y symbol"
Line: "Line x1 y1 x2 y2 symbol"
Rectangle: "Rectangle x y width height symbol"
Circle: "Circle centerX centerY radius symbol"
Light: "Light x y symbol"
Save the configuration file.

Compile the program using a C++ compiler. For example, using g++:
g++ main.cpp -o ascii_art

Run the program, passing the configuration file as an argument:
./ascii_art file.txt

The program will generate the ASCII art based on the configuration file and save it to the specified output file (e.g., output.txt).

How to Get the Project on Your Computer:
1. Clone the repository or download the source code files:
   git clone <repository_url>
2. Open the project in your preferred C++ development environment or compile the source code using a C++ compiler.

Follow the instructions in the "How to Use" section to run the program and generate ASCII art.

Files:

- main.cpp: The main program that reads the configuration file, creates the shapes, and generates the ASCII art.
- output.txt: The output file where the ASCII art will be saved.
- config.txt: An example configuration file that you can modify to define the canvas, shapes, and light sources.

