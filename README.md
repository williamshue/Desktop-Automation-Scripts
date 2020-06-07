# Desktop Automation Scripts

This repository contains some of the scripts I use to automate actions on my computer.

## init.lua

[Hammerspoon](https://www.hammerspoon.org/) is a tool I use to manage windows on my laptop with keyboard shorcuts. A Lua script serves as the configuration for the tool. I have it configured for the following shortcuts to preform the following actions:

- cmd + Left: Move current window all the way to the left and take up half the screen
- cmd + Right: Move the current window all the way to the right and take up half the screen
- cmd + Up: Exapnd the current window to take up the entire screen

Note: enabling hammerspoon to run on startup with certain shortcuts may interfere with defaults, I expirenced this with cmd + W, I recommend avoiding these key combonations if they might casue this issue.

## clearNotification.py

[PyAutoGUI](https://github.com/asweigart/pyautogui) is another tool which allows one to control their mouse and keyboard with python scripts. I've added a super simple script that will click the clear button on a macos notification, one will likely need to adjust the coordinates to match their monitor size.

## Key Remapping

I also suggest remapping 'caps lock' to 'escape' for vim users. This can easily be done in macos via System Prefrences > Keyboard > Modifier Keys

## Dock Hiding

Although it is likely fastest to open applications via a cmd + space spotlight search and 'enter' it can be nice to make use of the dock in macos. To keep the dock entierly out of the way to free up as much screen space as possible while still allowing immediate access to it I recommend hiding it and [eliminating the animation for displaying it.](https://9to5mac.com/2017/05/09/macos-dock-autohide-animation-video/) This when the user moves their mouse to the bottom of the screen to display it, it will take zero time for it to appear.
