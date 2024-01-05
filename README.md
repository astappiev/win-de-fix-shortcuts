# German keyboard with swapped Undo (Ctrl+Y) and Redo (Ctrl+Z) shortcuts

## Introduction
Ah, so convenient it is to use Ctrl+Z over the whole keyboard... good gymnastics for our fingers, right?

## Layout
The keyboard layout is an original German layout without any modifications. You still type `Z` when you press the key marked with `Z` and `Y` when you press `Y`.

However, on a system level, all key combinations that use `Ctrl+Z` and `Ctrl+Y` will be swapped.

## How to Build or Install
You can download the latest installer from the [releases tab of this repo](https://github.com/astappiev/win-de-fix-shortcuts/releases).

If you prefer to build from source, you can open the .KLC source file in Microsoft Keyboard Layout Creator.
You can use [this great guide](https://msklc-guide.github.io/) on how to work in this program.
After opening the file, choose Project > Build DLL and Setup Package in the menu to create an installer.

## Alternative approach
If for some reason, it doesn't work for you, there is another way of achieving this via AutoHotKey. [I described it here](https://gist.github.com/astappiev/4046a16f66af4416a3795e73f5e32a2e).
