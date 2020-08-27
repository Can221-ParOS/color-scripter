# color-scripter
** Clone the repo to your Home directory! otherwise the program will be unable to load the color scripts. **

A small python script that selects a random color script from a directory, and runs it to display it in the terminal. For Unix based operating systems only. 

(Also works in a TTY (though colors arent properly displayed) Fancy!)

The program loads colorscripts from the 
``` color-scripter/color-files/ ```
directory (located in ~/), and the program will automatically start using new scripts that are added to this directory.

To make a random color script appear every time you open your terminal,
this line can be added to a .bashrc or .zshrc file after the "source" section:

``` python $HOME/color-scripter/coscripter ```
