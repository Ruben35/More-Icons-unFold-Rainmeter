# Contributing :balloon:
To create a new button, you need to:

1. **Fork** this repository.
2. **Download** the following files:
```
-Left Button Template.psd
-Right Button Template.psd
-Left Button Template.ini
-Right Button Template.ini
```
3. **Edit** the _Right/Left Button template.psd_ files in order to put your button. (it is necessary to have Adobe Photoshop or similar to open these files).
4. **Save** the buttons as:
```
-NAME_OF_YOUR_BUTTON Left.png
-NAME_OF_YOUR_BUTTON Right.png
```
5. **Edit** the _Right/Left Button .ini_ files changing the words:
    - _YOURNAME_: This is your name,
    - _NAMEHERE_: This is the name of the program (your button)
    - _PATHHERE_: This is the path to start your program (if you dont know it, just put the name of the program and the word "PATH").
5. **Save** the edited _.ini_ files **as**:
```
-NAME_OF_YOUR_BUTTON Left.ini
-NAME_OF_YOUR_BUTTON Right.ini
```
6. Then **create** a folder with the name of your button on the root of the repository and **save** your files like this:
```
├───NAME_OF_YOUR_BUTTON
│   └───Transparent
│           NAME_OF_YOUR_BUTTON Left.ini
│           NAME_OF_YOUR_BUTTON Right.ini
├───Buttons
│   └───Transparent
│           NAME_OF_YOUR_BUTTON Left.png
│           NAME_OF_YOUR_BUTTON Right.png
```
7. Finally, **commit** your changes on your branch and **make** a pull request saying what are you adding.