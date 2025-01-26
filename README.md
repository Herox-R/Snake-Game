# Snake Game
 The Snake game is a simple version of the classic Snake game where the player controls a snake that moves around the screen and eats food to grow longer.

# Technologies
- C# (Programming Language)
- WPF (Windows Presentation Foundation) (UI Framework)
- XAML (UI Markup Language)
- BitmapImage (For loading images)
- MVVM (Model-View-ViewModel) (Design Pattern for UI separation)
# Frameworks and Components
- .NET Framework 4.8
- WPF Controls (Grid, TextBlock, Border, UniformGrid, etc.)
- Image Management (For Snake, Food, etc.)
- Event Handling (KeyDown event handling)
- Timer (For game loop or periodic updates)
- Game Loop (To update game state)
= Model-View-Controller (MVC) (Software Design Pattern)

# How it works 
Main Components:
- Direction Class: Manages the possible movement directions for the snake (up, down, left, right). Each direction is represented as an offset in rows and columns.
- Grid (GameState Class): This represents the game grid where the snake moves. It keeps track of the grid's state, including the snake's position, food placement, and whether the game is over.
- Snake Movement (GameState Class): The snake moves by updating its head position based on the current direction. The body follows the head, and if the snake eats food, the snake grows longer.
-MainWindow (UI): This is the WPF window that displays the grid and handles user input (e.g., key presses to control the snake).

# Author 
- Sylvester
