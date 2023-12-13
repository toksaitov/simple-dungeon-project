Simple Dungeon Crawler
======================

![Dungeon Crawler](https://i.imgur.com/kS2rLP9.png)

The primary goal of these projects is to build a simple [Dungeon Crawler](https://en.wikipedia.org/wiki/Dungeon_crawl) game written in C++ using the raylib graphics library.

The game should adhere to the best Structured and Procedural Programming principles. You should strive to effectively utilize structured programming constructs such as variables, constants, selection constructs, the ternary operator, and loops. Additionally, endeavor to achieve procedural decomposition of your code into functions. Your code should also be consistently formatted, following the best practices of coding style. This includes proper naming, indentation, use of white spaces, blank lines, and comments.

Use the provided [files](https://drive.google.com/file/d/1z5s3KgPg6p1eEv5OWEwB65_Of44786W4/view?usp=share_link) as a starting point for your game. You can modify the files as you see fit.

Be creative, but ensure to implement at least the following elements outlined below.

## Project #1

### Required Game Elements:

* Title Screen: The game should start with a 'Title' screen featuring a game logo and a message to start the game.

![Title Screen](https://i.imgur.com/ytQVicK.png)

* Game Screen: By pressing the key to start the game, the program should transition to the gameplay screen, allowing the player to navigate their character through a series of maze-like levels. In project 1, the objective is to reach the end by passing through all the levels.

![Game Screen, Level 1](https://i.imgur.com/rqGzRXN.png)
![Game Screen, Level 2](https://i.imgur.com/IrljFzC.png)

* Pause Screen: The player should be able to pause the game by pressing the `ESC` key. A 'Pause' screen should appear with an option to resume the game. Pressing the `ESC` key again should also unpause the game.

![Pause Screen](https://i.imgur.com/708RtU6.png)

* Victory Screen: Upon passing through all the levels, a victory screen should display a message, allowing the player to return to the 'Title' screen.

![Victory Screen](https://i.imgur.com/g4hXtrf.png)

## Project #2

### Required Game Elements:

Enhance your game by adding at least the following features:

* Five or more new levels.
* Three or more different game elements, one of which should be an enemy.
* A new game screen that appears when the player loses the game.
* Three or more different sound effects.
* Music on the title screen and during gameplay.
* One or more new gameplay mechanics. Be creative.

## Additional Requirements:

* Develop the code independently and maintain a detailed project commit history. Points will not be awarded if there is suspicion of code plagiarism (even if unfounded).
* Create a `Readme.md` with your game's description, and a list of the features from Project 2 that you have implemented.

## Deliverables

* Organize the game code into separate files for similar functions.
* Place the program's main entry point in the `dungeon.cpp` file.
* Develop the game in your private course directory and store the sources in a directory named `projects`. If the `Readie.md` file instructs using different directory names, disregard that requirement.
* Include all source code and supporting files (images, fonts, sounds, etc.) required to run the game.

Upon completion, your `projects` directory should look something like this:

```
.
├── data
│   ├── fonts
│   │   └── ...
│   ├── images
│   │   └── ...
│   └── sounds
│       └── ...
├── dungeon.cpp
├── <various header files>.h
```

Commit and push your work periodically. Finally, submit the last commit URL before the deadline to Canvas.

## Deadline

Check Canvas for information about deadlines.

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
