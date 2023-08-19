# RTS-Keyboard-Layout
This is a keyboard layout for the 19<sup>th</sup>-century Romanian Transitional Script (RTS). It includes the most common characters used in Romanian texts from the 19<sup>th</sup> century, including both Cyrillic and Latin letters.

> [!NOTE]
> \+ previous tier's benefits

> **PLUS:** Body of the note
> This can <span style="color:blue">span</span> multiple lines

## Installation
1. Copy the `RTS.bundle` file to one of the following locations:
* `/Library/Keyboard Layouts` (for all users)
* `~/Library/Keyboard Layouts` (for the current user only)

2. Then, log out and log back in.

The keyboard layout will be available in the "Romanian (Cyrillic)" category of the "Input Sources" sheet of the "Keyboard" page of the "System Settings" app.

> **TIP:**
> Visit [this page](https://penteliuc.com/box-editor-for-tesseract) to test out the keyboard layout. Use the Highlighter settings page to diferentiate between Latin and Cyrillic characters.

## Keys
The keyboard layout follows the Romanian QWERTY layout and replaces keys to include Cyrillic characters in the same positions as their phonetic Latin counterparts[^1].
<!-- Exceptions are `z` and `î`, which are not part of the Cyrillic alphabet. -->
The following image shows the layout of the keyboard:
![Image](/Images/Keyboard-Screenshot-01.png)
`Shift` key behaves as expected, capitalizing letters:
![Image](/Images/Keyboard-Screenshot-02.png)
Pressing the `Option` key will show variants for each key, which sometimes include Latin letters, or allow access to different Cyrillic letters.
The keys corresponding to `1`, `2`, and `3` are *dead keys* allowing for typing the combining characters ` ̀` (grave accent), ` ́` (acute accent), and ` ꙼ ` (Cyrillic Kavyka):
![Image](/Images/Keyboard-Screenshot-03.png)
`Option` + `Shift` will capitalize the variations:
![Image](/Images/Keyboard-Screenshot-04.png)
Normal keyboard shortcuts are still accessible by pressing `Command`:
![Image](/Images/Keyboard-Screenshot-05.png)

### Reporting Issues
If you find any issues with the keyboard layout, please [open an issue](https://github.com/mariuspenteliuc/RTS-Keyboard-Layout/issues/new/choose) on GitHub.
I will try to fix it as soon as possible.

<!-- foot note -->
[^1]: Not all Cyrillic characters map onto Latin characters and vice-versa.
The layout is designed to be as intuitive as possible for typing 19<sup>th</sup>-century Romanian, but some characters are not available in the same positions as their Latin counterparts.
