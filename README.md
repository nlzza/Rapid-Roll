# Rapid-Roll

This is an implementation of the classic Nokia game, "Rapid Roll", in x86 assembly.
The game’s objective is to ensure that the ball remains on the screen while the screen scrolls down.
The player can move the ball left or right. To keep up with the pace of the scrolling screen, the player
has to jump down onto platforms that appear in random locations on the screen.
The game ends if the player fails to jump down onto a platform, either by being slow or by missing the platform entirely.
Once the game ends, the score is displayed alongside the high score.

## How to run locally

First clone the project. Then go to _Includes.inc_ in the _include_ directory and change the paths
according to the location where masm32 and irvine are installed in your system.
Similarly, in _run.bat_, the path of masm32 in line 3 may need to be changed.
Meanwhile, in line 4, change the path to the location where you have cloned the project.

Once this is accomplished, you are ready to run the game. Simply execute ./run.bat main.ASM in the command line and enjoy!
