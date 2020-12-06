Use Mac keyboard with AutoHotkey under Windows
==============================================

This [AutoHotkey](https://www.autohotkey.com/) configuration file makes usual keyboard shortcuts work with an Apple keyboard on Windows. It has been testet with a german keyboard layout, but should work under different layouts as well.

If it's not working for applications running with admin permissions, it might be the problem that AHK is not, see [this question on StackOverflow](https://stackoverflow.com/a/8457852/723769).

This is a fork of [stroebjo's](https://github.com/stroebjo/autohotkey-windows-mac-keyboard) configurations with the following additions for Chrome keyboard shortcuts: 


- Delete key is mapped to F6 (Couldn't find a way to map to the eject key) 
- Command + D maps to adding the individual page to bookmark 
- Command + R maps to refreshing the page
- Command + Option + Left/Right maps to shifting the tabs left/right

Installation
------------

- Install [AutoHotkey](https://www.autohotkey.com/) 
- Run the `MacKeyboard.ahk` file
- Put the `MacKeyboard.ahk` file or a shortcut to the file in your Autostart folder to run it automatically on startup.
