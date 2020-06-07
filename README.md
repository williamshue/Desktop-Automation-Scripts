# Desktop Automation Scripts

This repository contains some of the scripts I use to automate actions on my computer.

## init.lua

[Hammerspoon](https://www.hammerspoon.org/) is a tool I use to manage windows on my laptop with keyboard shorcuts. A Lua script serves as the configuration for the tool. I have it configured for the following shortcuts to preform the following actions:

- cmd + Left: Move current window all the way to the left and take up half the screen
- cmd + Right: Move the current window all the way to the right and take up half the screen
- cmd + Up: Exapnd the current window to take up the entire screen

## clearNotification.py

[PyAutoGUI](https://github.com/asweigart/pyautogui) is another tool which allows one to control their mouse and keyboard with python scripts. I've added a super simple script that will click the clear button on a macos notification, one will likely need to adjust the coordinates to match their monitor size.

