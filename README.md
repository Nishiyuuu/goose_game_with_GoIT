# ***Goose game***

# **Introduction**

---

"Goose" is my first 2D video game that I developed during a free Python marathon at the GoIT school. During this marathon, we learned the basics of Python programming language syntax and how to integrate other libraries into our projects. The library used for developing the video game is called "Pygame." It is quite popular among beginners in game development as it provides a straightforward syntax and clear documentation.

# **pygame**

## **Description of the Pygame Library**

---

Pygame is a library for programming games in the Python programming language. It provides a powerful and simple interface for creating 2D games and interactive applications. Pygame is based on the SDL (Simple DirectMedia Layer) library and gives Python access to its functionality through a convenient API.

## **Key Components of Pygame**

---

- Graphics module: Pygame offers extensive graphics capabilities, allowing you to create windows, display images, create animations, manage colors, and textures.
- Sound module: Pygame enables the use of sounds and music in your game.
- Event handling module: Pygame provides convenient functions for handling events such as key presses, mouse clicks, window resizing, and more.
- Animation and effects module: Pygame allows you to create various visual effects and animations for your game.
- Time management module: Pygame lets you control time in your game.

## **Using Pygame**

---

- Initializing Pygame: The first step in using Pygame is to initialize the library and create essential objects such as the game window.
- Creating game objects: You create various objects for your game, such as characters, items, enemies, etc.
- Event handling and player interaction: Pygame allows you to handle user input and respond to player interaction with the game.
- Animation and effects: You can create various animation and sound effects for your game.
- Game loop: Pygame uses a game loop for continuous updating of the game state and displaying new frames on the screen.

## **Popularity of Pygame Among Programmers**

---

Pygame is very popular among programmers because it provides a convenient and powerful toolkit for creating various games and interactive applications. It is suitable for beginners in game development as well as experienced developers looking for a quick and efficient way to create games in Python.

## **Installing Pygame**

---

In order to install pygame, you must first install Python.

#### [Windows version](https://www.python.org/ftp/python/3.12.3/python-3.12.3-amd64.exe) | [macOS version](https://www.python.org/ftp/python/3.12.3/python-3.12.3-macos11.pkg)

Linux:

```bash

sudo apt-get install python3

```

and install pygame:

```bash

pip install pygame

```

## **creating a new project**

---

- After installing Pygame, create a folder for your project and import Pygame into your Python script:

```python

import pygame

```

- Initialize Pygame to start working with it:

```python

pygame.init()

```

- Create the game window:

```python

screen = pygame.display.set_mode((width, height))

```

## **Game loop**

---

- Create the main game loop to handle events, update the game state, and display frames.

```python

while running:
    for event in pygame.event.get():
        if event.type == pygame.QUIT:
            running = False
pygame.display.flip()

```

## **Result**

---

After completing the development of the "Goose Game with GoIT," the following results were achieved:

1. Creation of a first 2D video game: Successfully created a full-fledged 2D video game, which is a first experience in game development using the Python programming language and the Pygame library.
2. Programming and design skills: Gained valuable practical experience in programming in Python and in developing graphical design, object interaction, and game environment interaction during game development.
3. Using the Pygame library: Mastered the use of the Pygame library for creating graphical games, animations, and handling user events.

## **Conclusion**

---

The process of developing the "Goose Game with GoIT" was a significant step in learning and practically applying programming and game development knowledge. Using the Pygame library allowed creating an interesting and attractive game with unique gameplay. This project not only showcased my programming skills but also helped understand the fundamental principles of game development and influenced my desire to grow in this field. Such experience is crucial for my future professional growth and success in the game development industry.

---
https://github.com/Nishiyuuu/goose_game_with_GoIT/assets/108515216/a777fb6a-9b2f-4ef5-b0a5-6384fed00b2a
