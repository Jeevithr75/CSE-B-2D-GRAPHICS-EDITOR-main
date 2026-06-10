# 2D Graphics Editor in C

## Project Description

This project is a menu-driven 2D Graphics Editor implemented in C using a 2D character array as the drawing canvas.

The canvas is initially filled with the character `_` (underscore), and graphical objects are drawn using the character `*` (asterisk).

The program allows users to create, modify, delete, and display graphical objects on the canvas.


## Features

- Draw Rectangle
- Draw Line
- Draw Triangle
- Draw Circle
- Display Canvas
- Display Object List
- Delete Objects
- Modify Objects
- Menu Driven Interface
- Uses 2D Character Array for Storage


## Data Structure Used

- 2D Character Array (`canvas[ROWS][COLS]`)
- Structure (`Shape`) to store object information
- Array of Structures (`objects[]`) for object management


## Menu Options

```text
1. Draw Rectangle
2. Draw Line
3. Draw Triangle
4. Draw Circle
5. Display Canvas
6. Display Objects
7. Delete Object
8. Modify Object
9. Exit
```

---

## Compilation

Compile the program using GCC:

```bash
gcc "final code.c" -o graphics_editor.exe


---

## Execution

Run the program:

```bash
.\graphics_editor.exe


## Sample Output

```text
========== OBJECT LIST ==========

ID: 1 | Rectangle
ID: 2 | Line
ID: 3 | Triangle
ID: 4 | Circle
```


## Concepts Used

- Arrays
- Structures
- Functions
- Menu Driven Programming
- 2D Graphics Representation
- Object Management
- Bresenham Line Drawing Algorithm

---

## Author

Name: JEEVITH R

SRN: R25EF106

Course: C Programming Lab

---

## GitHub Repository
https://github.com/Jeevithr75/CSE-B-2D-GRAPHICS-EDITOR-main.git
