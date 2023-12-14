Simple Dungeon Crawler
======================

![Dungeon Crawler](https://i.imgur.com/kS2rLP9.png)

The primary goal of these projects is to build a simple [Dungeon Crawler](https://en.wikipedia.org/wiki/Dungeon_crawl) game written in C++ using the [raylib](https://www.raylib.com) graphics library. In this game, the player navigates a character through a series of maze-like levels, collecting items, avoiding enemies, and solving puzzles.

The game should adhere to the best structured and procedural programming principles. You should strive to effectively utilize structured programming constructs such as selection constructs and loops. Additionally, endeavor to achieve procedural decomposition of your code into functions. Ensure consistent formatting in your code, adhering to coding style best practices, including proper naming, indentation, use of white spaces, blank lines, and comments.

Use the provided [files](https://drive.google.com/file/d/1z5s3KgPg6p1eEv5OWEwB65_Of44786W4/view?usp=sharing) as a starting point for your game. You can modify the files as you see fit.

Be creative, and ensure to implement the following essential elements in your project, as outlined below.

## Project #1

### Required Game Elements:

* Title or Menu Screen: The game should start with a title screen featuring a game logo and a message to start the game. Alternatively, it could be a menu screen with options to start the game, view the instructions, or quit the game.

![Title Screen](https://i.imgur.com/ytQVicK.png)

* Game Screen: From the title or menu screen, the player should be able to start the game. The game screen displays the player's character, the maze, and the items. Players move the character using the keyboard and collect items by moving over them. The goal is to move from one level to the next by passing through the maze's exit. In Project #1, the objective of the player is to reach the end by passing through all the levels. There should be at least three levels in Project #1.

![Game Screen, Level 1](https://i.imgur.com/rqGzRXN.png)
![Game Screen, Level 2](https://i.imgur.com/IrljFzC.png)
![Game Screen, Level 3](https://i.imgur.com/kS2rLP9.png)

* Pause Screen: The player should be able to pause the game by pressing the Escape key. A 'Pause' screen appears with an option to resume the game. Pressing the Escape key again resumes the game.

![Pause Screen](https://i.imgur.com/708RtU6.png)

* Victory Screen: Upon passing through all the levels, a victory screen displays a congratulatory message, allowing the player to return to the title screen. Some animation, possibly from lab class exercises, should play in the background to indicate the game's completion.

![Victory Screen](https://i.imgur.com/g4hXtrf.png)

## Project #2

### Required Game Elements:

* New Levels: Add at least *five new levels* to the game. These levels should be more challenging than those in Project #1.

* New Game Elements: Introduce at least *three new elements* to the game. These could include new items, enemies, or obstacles. Be creative, but ensure one of these elements is an enemy.

* Game Over Screen: Implement *a 'Game Over' screen* that displays a message when the player loses the game, such as when colliding with an enemy. This screen should allow the player to return to the title screen.

* New Sounds: Add at least *three new sounds* to the game. These sounds could accompany actions like collecting an item, colliding with an enemy, or exiting the final maze.

* Music: Incorporate at least *one music track* into the game. This track should play on at least one of the screens. Ensure the track is royalty-free or that you have usage rights. Store the music files in the `data/music` directory and keep them reasonably sized.

* New Mechanics: Introduce at least one new gameplay mechanic. This could be a novel way to collect items, move the character, or interact with the maze. Let your creativity guide you.

## Additional Project #1 and #2 Requirements:

* Develop the code independently and maintain a detailed project commit history. Be aware that points will be withheld for any suspicion of code plagiarism, even if it's unfounded. Additionally, consistent progress must be evident in your project commit history to receive any points at all.

* Create a `Readme.md` file with a description of your game and a list of the features from Project #2 that you have implemented. Note that partially implementing some features is preferable to not implementing any.

* Ensure that the game is playable and contains all necessary files. It should be straightforward for the instructor to set up and start the game with minimal effort.

## Deliverables

* Develop the game within the `projects` directory. This directory should include a `data` subdirectory containing all game assets (images, fonts, sounds, etc.). Additionally, ensure the `projects` directory contains a `Readme.md` file detailing your game and listing the implemented features from Project #2. Disregard any previous instruction to name the project directory as `pr01` or `pr02`, as mentioned in the older `Readme.md`.

* Organize your code into a set of header files. Each header file should contain related function definitions. Please, add forward declarations for each function in the `globals.h` file to prevent circular dependencies.

* Place your main game loop in the `dungeon.cpp` file, which should include `globals.h` and all other necessary header files.

Upon completion, your `projects` directory should have an organized structure similar to the following example (you can provide a simple example or description here).

```
. (.idea, .gitignore, CMakeLists.txt, other lab dirs)
└── projects
    ├── data
    │   ├── fonts
    │   │   └── ...
    │   ├── images
    │   │   └── ...
    │   ├── music
    │   │   └── ...
    │   └── sounds
    │       └── ...
    ├── dungeon.cpp
    ├── globals.h
    ├── <various header files>.h
    └── Readme.md
```

Commit and push your work at regular intervals, such as daily or after significant changes. Finally, submit the URL of the last commit to Canvas before the deadline.

## Deadline

Refer to the specific course or assignment page on Canvas for detailed information about deadlines.

## Links

### raylib

* [Wiki](https://github.com/raysan5/raylib/wiki)
* [Cheatsheet](https://www.raylib.com/cheatsheet/cheatsheet.html)
* [Examples](https://www.raylib.com/examples.html)

### Tools

* [Piskel](https://www.piskelapp.com)
* [bfxr](https://www.bfxr.net)

## Books

* Introduction to Programming with C++, 3rd Edition by Daniel Liang
