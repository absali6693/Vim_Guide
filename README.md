# VIM

### Set-up

 Vim starts in command mode.
 Press ```I``` to enter to the insert mode.
 Use escape to exit insert mode.
 Use ```:q ``` to quit(while in commnad mode)
 Use ```:w ``` ri save
 You can use ```:wq ``` to save and exit

 ### Enable syntax highlighting
```sh
:syntax on
```
 ### Displaying line numbers
```sh
:set number
```

Use ```O``` in command mode instead of ```I``` to enter into insert mode and enter a new line below your curser.
```SHIFT + O``` create a new empty line above your curser.

To go to the bottom of the file use ```SHIFT + G``` in command mode

To open two documents in split window use
```sh
vim -O <file1> <file2>
```
To switch between files in split mode use:
```sh
CTRL+W+<ARROW KEYS (left or right)>
```

To execute a command
```sh
:!<command>
```

If you want to run the current program say ```python program.py```, You can use:
```sh
:!python %
```
Vim will automatically substitute the name of current program in place of %


## Tip
To check the exit status of a program that you just executed, in the terminal run
```sh
echo $?
```

To run a python program without having to right python every time, at the top of your python code add

```sh
#!<path to python>
```