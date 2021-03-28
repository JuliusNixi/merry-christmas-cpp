# Merry Christmas CPP
A simple, small, command line program for Windows written in C++. It print a beautiful and colorful Christmas tree. Useful to get into the Christmas mood. 🎄

## How to Download & Install:
This program does not require any installation! It's a standalone .exe file which only needs to be downloaded and executed. To do download:

1. Download this repo. You can do it in many different ways, the easiest is to click on 'Code' and then 'Download ZIP'.
2. If you have downloaded the .ZIP file extract it to any location you want. If you cloned this repo with git (or other ways) you should have the folder ready to use (already unzipped).

## How to Execute:
There are two ways to run the file:

* Without passing arguments, using default printing.
* Passing arguments to customize printing.

Without passing arguments, using default printing:

1. Simply open the downloaded folder (unzipped) (this repo).
2. Open the 'bin' subfolder.
3. Double click on 'MerryChristmas.exe'.
4. Enjoy the view! 💙

Passing arguments to customize printing:

1. Press 'WINDOWS + R' on keyboard.
2. Write 'cmd' in the window and press 'ENTER' on keyboard.
3. In the terminal (the black window) you will have opened, use the command 'cd *PATH*' to move in the downloaded folder (unzipped) (this repo). Obviously replace '*PATH*' in command with the path/folder where you want to enter. Example: 'cd C:\Users\Giulio\Desktop\', 'ENTER' on keyboard and then 'cd  merry-christmas-cpp', 'ENTER' on keyboard.
4. When you are inside the right folder type 'cd bin' and press 'ENTER' on keyboard.
5. Type 'MerryChristmas.exe help' and press ENTER on keyboard.
6. You should see a help screen. Follow it to pass the right arguments to the program and customize the print.
7. At the end you should have a command similar to this one: 'MerryChristmas.exe 1 1 1 1 X 10 + - 0' then 'ENTER' on keyboard.
8. Enjoy the view! 💙

## Recompile:
If you want to modify the source code and recompile the program, it's quite easy to do it if you have a minimum of experience with computer science. There are two ways:

* Use a C++ IDE as support.
* Recompile manually.

Use a C++ IDE as support:
If you have an C++ IDE installed on your computer i think i have not to explain much...

1. You should already have a C++ compiler installed from the IDE.
2. Open the file 'MerryChristmas.cpp' in the repo root with the C++ IDE.
3. Edit the file as you want.
4. Recompile the file using C++ IDE support.
5. You should get the new .exe file.

Recompile manually.

1. You need to install a C++ compiler if you don't already have it. There are several. I recommend 'MinGW'. Google it. Download and Install it.
2. Be sure to add the 'g++.exe' and 'gcc.exe' files to the system variables (path). Are located in the 'bin' subfolder contained in the MinGW root folder.
3. Open a system shell (cmd). Go to the repo folder using 'cd' command.
4. Run the command: 'g++ MerryChristmas.cpp -o bin/MerryChristmas.exe' and then 'ENTER' on keyboard.
5. ALTERNATIVELY If you have problems with the previous command you can try to use this: 'gcc MerryChristmas.cpp -o bin/MerryChristmas.exe -lstdc++' and then 'ENTER' on keyboard.
6. You should get the new .exe file in the 'bin' folder.

## Change Default Settings:
It's possible to modify the default settings, that are called if no arguments are passed to the program. To do this:

1. Open the 'MerryChristmas.cpp' file (contained in the root of the repo) with a text editor, preferably an IDE that supports C++, but not necessary.
2. Modifies the vars contained between the two large blocks of initial comments, these:
```c++
    bool PRINT_TREE = true;
    bool PRINT_MERRYCHRISTMAS = true;

    bool COLORS = true;

    bool CHRISTMAS_BALLS = true;
    char CHRISTMAS_BALLS_CHAR = 'O';

    int SIZE = 20U;

    char TREE_CHAR = '*';
    char TRONK_CHAR = '|';

    bool PRINT_SIGNATURE = true;
 ```
 3. Follow the instructions above to recompile.

##Help Page

![Error: 'help_screenshot.png' not found.](https://github.com/juliusnixi/merry-christmas-cpp/blob/main/help_screenshot.png?raw=true)

