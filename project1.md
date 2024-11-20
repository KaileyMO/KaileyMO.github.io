[Back to Portfolio](./)

Puzzle Game
===============

-   **Class: Object-Oriented Programming CSCI 325** 
-   **Grade: 90** 
-   **Language(s): Java** 
-   **Source Code Repository:** [Puzzle Code](https://github.com/KaileyMO/Puzzle-Game/tree/main)  
    (Please [email me](mailto:kmowens@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

This program is a 2-D puzzle game created in Java code. It contains three levels; each level contains a yellow key that the player must unlock by completing each level's unique puzzle. Once the player collects the level's key, a black door appears and the player goes through the door and to the next level. The player completes these puzzles by moving left, moving right, and jumping.

**Controls:**  
Move left- A  
Move right- D  
Jump- W  
Open menu- Shift

This was a group project, so I did not create the entire game but instead primarily constructed the second level and connected all three levels cohesively.

## How to compile and run the program

To run this program, your device must have Java installed. This program is created on [Netbeans 19](https://netbeans.apache.org/front/main/download/nb19/), so Java JDK 20 should be adequate. Java 20 can be downloaded with [oracle](https://www.oracle.com/java/technologies/javase/jdk20-archive-downloads.html) if necessary.

Assuming Netbeans is the preferred method for compiling and running this program, after its installation, open the application and drag the folder of this project's unzipped source code into the starter Netbeans space (Fig 1).

![screenshot](images/netbeanInstallation.png)  
Fig 1. Drag the code folder into Netbeans.

Access the Puzzle_Game_GUI_Finished -> Source Packages -> <default package> and click on one of the .java files, such as Panel.java. This opens the class's code and will run the project it is connected to (Fig 2).

![screenshot](images/netbeanInstallation2.png)  
Fig 2. Opens a file from the project.

Click the green arrow at the top of the program to run it (Fig 3).

![screenshot](images/netbeanInstallation3.png)  
Fig 3. Runs project.

## UI Design

There are three levels. The game revolves around this 2-D animated setup (Fig 4), which is the starting position upon loading up the game, where most every object is created from squares. The blue square is the player character and other objects have unique characteristics, like some move on their own and others can be touched by the player.

![screenshot](images/puzzle_game_start.png)  
Fig 4. Game starting screen.

Before the levels, pressing shift on the keyboard opens up a menu screen. Pressing "Reset" will reset the levels and pressing "Exit" will close the program and stop its run.

![screenshot](images/puzzleImages/menuScreen.png)  

### Level 1:

The first level requires a button to be pressed for the key to appear. The player will jump (Fig 5) up to the lower platform (Fig 6):

![screenshot](images/puzzleImages/one.png)  
Fig 5. Player jumping to first platform.

![screenshot](images/puzzleImages/two.png)  
Fig 6. Player after landing on first platform.

Another obstacle is the moving platform now located to the player's right. The player must time the jump then jump on to it. Once on this platform (Fig 7), the highest ledge containing a red object is accessible (Fig 8).

![screenshot](images/puzzleImages/three.png)  
Fig 7. Player after landing on moving platform.

![screenshot](images/puzzleImages/four.png)  
Fig 8. Player on the highest platform next to red object.

Now the player must push the red object to the floor (Fig 9) and then into the hole with the button (Fig 10).

![screenshot](images/puzzleImages/five.png)  
Fig 9. Player just pushed the red object off the ledge.

![screenshot](images/puzzleImages/six.png)  
Fig 10. Player pushing the red object to the hole containing the button.

Successfully pressing this button causes the level's yellow key to appear (Fig 11). The player goes over it to collect it. This opens the black door and adds +1 to the key counter at the top right of the game screen (Fig 12).

![screenshot](images/puzzleImages/seven.png)  
Fig 11. Yellow key appear after the object clicks the button.

![screenshot](images/puzzleImages/eight.png)  
Fig 12. Player collects key and a black door appears.

The player has completed the puzzle. Now, the player gets teleported to the next level after running through the door.

### Level 2:

The second level contains four small squares bouncing around the box that the game takes place in/the player walks around in. The goal is to change the colors of the squares so that the four colors of the bouncing squares matches with the colors of the static squares at the bottom of the screen, below the playable area. As the round begins, only one square is visible and bouncing around the area (Fig 13).

![screenshot](images/puzzleImages/nine.png)  
Fig 13. The starting position of the second level.

As the color of the bouncing cube is first changed, another bouncing square is introduced until both the squares get their colors changed enough for all the four squares to begin bouncing (Fig 14). Colors change as the player touches the squares, so the player will jump around until all the squares are at the correct colors.

![screenshot](images/puzzleImages/ten.png)  
Fig 14. Game running with the player trying to accurately convert the square colors.

![screenshot](images/puzzleImages/eleven.png)  
Fig 15. Additional action shot of player attempting to change the square colors.

After the colors are all matching (1 yellow, 1 red, 2 purples), all the squares turn permanently yellow and a key appears on the floor (Fig 16). Collecting the key opens the black door and adds +1 to the key counter at the top right of the game screen (Fig 17).

![screenshot](images/puzzleImages/twelve.png)  
Fig 16. Puzzle completed and a key has appeared.

![screenshot](images/puzzleImages/thirteen.png)  
Fig 17. Player collected the key.

The player has completed the puzzle. Going through the open door leads to the third and final puzzle.

### Level 3

This third puzzle is unique because it does not take place in the typical GUI format. Instead, temporarily leave the GUI and go to the text editor from where the program has been run. The first part of the third level will be displayed and waiting for the player to answer (Fig 18). The third level is a text-based math game that requires the user to answer true or false to the math question asked. It contains two parts, displayed as levels #1 and #2 that both contain three questions that must be answered correctly in a row.

![screenshot](images/puzzleImages/fourteen.png)  
Fig 18. Start of level 3 (the math game).

Getting the answers correct will prompt a short congratulatory message to pop up so the player knows the answer was right (Fig 19).

![screenshot](images/puzzleImages/fifteen.png)  
Fig 19. Correct answers.

If the player gets the answer incorrect, a message informs the player what level they failed in and the math level is reset to the beginning of the level (Fig 20).

![screenshot](images/puzzleImages/sixteen.png)  
Fig 20. Incorrect answer.

Any answer aside from true or false results in an error and a message pops up prompting the player for an adequate answer (Fig 21).

![screenshot](images/puzzleImages/seventeen.png)  
Fig 21. Unidentifiable answer.

The player must correctly answer the total of six questions from the combined two parts to pass the entire level. Once accomplished, a winning message appears and the player can collect a key in the GUI screen to allow the third level's door to appear (Fig 22).

![screenshot](images/puzzleImages/eighteen.png)  
Fig 22. Finishing game.

After passing through the door, the player has successfully completed the Puzzle Game program.

## 3. Additional Considerations

For the executable .jar file, it is best to run it using a system such as command prompt (cmd). This will allow the program to run the third level since the level requires a screen to print its text. In cmd, open the folder holding the .jar file and run the executable.

```bash
cd ./folder-with-project
java -jar Puzzle_Game_GUI_Finished.jar
```

Additionally, this executable may require Java JDK 20 to be run on. That may be downloaded with [oracle](https://www.oracle.com/java/technologies/javase/jdk20-archive-downloads.html) if necessary.


Be aware that the third level is not in the Puzzle Game GUI tab, but instead is composed of text to screen. The user will need to temporarily leave GUI and go to where the program is running to complete the last puzzle with text.

[Back to Portfolio](./)
