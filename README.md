# 2D Graphics Editor

## Overview
A simple C-based 2D Graphics Editor that allows users to draw and manage basic geometric shapes on an ASCII canvas. The project demonstrates basic computer graphics concepts and data structures in C.

## Features
- Draw Line, Rectangle, Circle, and Triangle
- Store multiple graphic objects
- Delete existing objects
- Render and display shapes on a canvas
- Menu-driven interface

## Canvas Specifications
- Width: 80
- Height: 24
- Empty Pixel: `_`
- Filled Pixel: `*`

## Algorithms Used
- DDA (Digital Differential Analyzer) Line Drawing Algorithm
- Midpoint Circle Drawing Algorithm

## Menu Options
```text
1. Add Object
2. Delete Object
3. Modify Object
4. Display Picture
5. List Objects
0. Exit
```

## Functions
- `clearPicture()` – Clears the canvas
- `displayPicture()` – Displays the canvas
- `setPixel()` – Sets a pixel on the canvas
- `drawLine()` – Draws a line using DDA
- `drawRectangle()` – Draws a rectangle
- `drawCircle()` – Draws a circle
- `drawTriangle()` – Draws a triangle
- `renderAllObjects()` – Renders all valid objects

## Compilation and Execution

### Compile
```bash
gcc graphics_editor.c -o graphics_editor
```

### Run (Windows)
```bash
graphics_editor.exe
```

### Run (Linux/Mac)
```bash
./graphics_editor
```

## Limitations
- Modify Object option is not implemented
- List Objects option is not implemented
- No validation for exceeding maximum object limit
- ASCII-based graphics only

## Learning Outcomes
- Structures and Unions in C
- Enumerations
- Arrays
- Modular Programming
- Basic Computer Graphics
- DDA Line Drawing Algorithm
- Midpoint Circle Algorithm

## Author
2D Graphics Editor Project in C
