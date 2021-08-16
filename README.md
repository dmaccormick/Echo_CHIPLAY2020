# Echo - CHI PLAY 2020
Daniel MacCormick and Loutfouz Zaman

This repository is supplementary to the full paper published and presented at CHI PLAY 2020 entitled "Echo: Analyzing Gameplay Sessions by Reconstructing Them From Recorded Data". The paper can be seen on the ACM Digital Library here: https://dl.acm.org/doi/10.1145/3410404.3414254.

This repository holds two main items:

1) The Unity package for Echo, containing all of its source code.
2) An executable version of Echo.

Unity Package:
-----------
- The Unity package can be imported into a Unity project.
- It contains all of the source code for Echo as well as all of the objects needed for setup.
- There are two scenes inside of Echo Assets / Scenes
	1) The first is an example recording scene. This can be used as a reference for setting up Echo within another project.
	2) The second is a visualization scene. This can be used to visualize recorded data provided the required assets are in the same project. You can load in log files by pressing the settings button in the top left and entering the correct path.

Executable Version:
-----------
- If you wish to try out Echo's visualization system without setting up the recording system, this can be done here.
- Included alongside this is a unique set of log files for the car and airplane games.
- After starting the exe, you will see a menu that has two buttons: "Airplane" and "Car".
- Click on the button for the data that you want to view. Echo will load up a scene that looks empty except for its UI.
- Press the settings button. Inside, there will be another button that will say "Load Airplane Log Files" or "Load Car Log Files". Press it.
- Echo will start to load in all of the files pertaining to that game. It is simpler to have it load all at once instead of loading in one at a time in this case.
- NOTE: THIS MAY TAKE A FEW MINUTES. It may say that it is not responding when it is actually still working in the background. 
- After a few minutes, some game objects should become visible behind the UI. This means that everything loaded correctly.
- You can then close the settings menu by pressing the button in the upper left of the screen once again. 
- At this point, you are free to try out all of Echo's features.
- If you want to try out the other game, you can go into the settings menu again and press the "Exit To Menu" button in the bottom right. From there, you can access the data for the other game.
- Once again, it will take a few minutes to load in the data from the other game as well.
- If you have trouble closing Echo when you are done with it, you can press Alt + F4 to exit.
 
