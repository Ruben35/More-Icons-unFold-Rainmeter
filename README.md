![GitHub All Releases](https://img.shields.io/github/downloads/Ruben35/Icons-unFold-Rainmeter/total.svg?color=informational) ![Github All Releases](https://img.shields.io/badge/license-GNU%20GPLv2-informational.svg) [![HitCount](http://hits.dwyl.io/Ruben35/https://github.com/Ruben35/Icons-unFold-Rainmeter.svg)](http://hits.dwyl.io/Ruben35/https://github.com/Ruben35/Icons-unFold-Rainmeter)
# More Icons Rainmeter unFold
In this repository you will be able to find different icons of the type **unFold** for **Rainmeter**. 

_reFold is a modified version of unFold where everything (except the icon) can be defined in the "ini" file._ Allows you to have different color text, background etc with minimal adjustments.

Added the configuration instructions below, and original README follows. 
## reFold Configuration
* Download the repository and make copies of the reFold-template_Left or reFold-template_Right 
* rename the folder for your app
* open the "ini" file and go to the ```[Variables]``` section
* configure your shortcut:
    - **Width, Height, maxWidth**: set the collapsed and expanded size of the button
    - **bgColor**: sets the background color and oppacity. Oppacity should be at least 1
    - **iconColor**: sets the icon color
    - **iconPath**: path to the icon. Place icons in the "Images" folder in the unFold skin 
    - **iconSize**: sets icon size
    - **textColor**: sets color of text
    - **textString**: text to be displayed on the button
    - **textFont**: font face. Windows installed fonts and fonts in "Fonts" folder are valid
    - **textWeight**: sets text weight. 100 = thin, 900 = bold
    - **textSize**: sets text size
    - **application**: Change this for your application. See bellow for more syntax
### application syntax
The simplest usage of the application is to simple put the full path to your application in square brackets and double quotes. Eg:\
```application = ["C:\Program Files (x86)\Google\Chrome\Application\chrome.exe"]```\
```application = ["C:\Users\Username\Documents\important.doc"]```

or if your application is already in your ```PATH``` environment variable, you can simply call:\
```application = ["chrome.exe"]```

If you'd like to open a program with paramaters that is done as such:\
```application = !Execute ["chrome.exe" rainmeter.net]```\
```application = !Execute ["chrome.exe" --incognito rainmeter.net]```

You can launch multiple programs at once by putting multiple actions there\
```application= !Execute ["chrome.exe" rainmeter.net]["Calc.exe"]```

In short, any action you can do with rainmeter is valid here.

## Contents :bookmark_tabs:
1. [What are the unFold skins?](https://github.com/Ruben35/Icons-unFold-Rainmeter#what-are-the-unfold-skins-computer)
2. [Pre-requirements](https://github.com/Ruben35/Icons-unFold-Rainmeter#pre-requirements-memo)
3. [Installation](https://github.com/Ruben35/Icons-unFold-Rainmeter#installation-wrench)
4. [How to contribute?](https://github.com/Ruben35/Icons-unFold-Rainmeter#how-to-contribute-balloon)
5. [Realeses Features](https://github.com/Ruben35/Icons-unFold-Rainmeter#realeses-features-clipboard)
6. [Authors and Credits](https://github.com/Ruben35/Icons-unFold-Rainmeter#authors-and-credits-book)
7. [License](https://github.com/Ruben35/Icons-unFold-Rainmeter#license-page_with_curl)
## What are the unFold skins? :computer:
The **unFold** skins are buttons that can be added on your desktop to use them as shortcuts.<br />
They have very nice designs and you can add them in the right/left of your desktop.
###### You can have something like this:
![Example of Desktop](https://user-images.githubusercontent.com/30848819/50526747-ca391480-0aa9-11e9-832c-b93dbca7e8d7.jpg)
###### Where the unFold buttons are:
![Example of Button](https://user-images.githubusercontent.com/30848819/50526744-bdb4bc00-0aa9-11e9-8cbb-c4e4d81813f8.jpg)
## Pre-requirements :memo:
Things you need to use **all** this skins on your desktop.
* Have the last version of Rainmeter (this project was developed in version 4.2.0) installed in your PC.
* Enough space on your disk to clone or download the skins.
* Know the path where the skins of Rainmeter are located.

If you just want to add **some** of this buttons you need:
* Have the others unFold buttons (if you don't have them, you can download the DevilRev one's [here](https://www.deviantart.com/devilrev/art/unFold-A-Launcher-618503449) or download a realease from [here](https://github.com/Ruben35/Icons-unFold-Rainmeter/releases)).

## How to contribute? :balloon:
If you want to contribute to this repository you can:
* **Open** issues in order to **give** me suggestions of new buttons.
* **Open** issues in order to **report** a bug.
* **Star** this repository.
* **Fork** this repository and **make** your own buttons, then **create** a pull request.

If you do the last thing, you should check the [CONTRIBUTING](https://github.com/Ruben35/Icons-unFold-Rainmeter/blob/master/CONTRIBUTING.md) file and the [CODE_OF_CONDUCT](https://github.com/Ruben35/Icons-unFold-Rainmeter/blob/master/CODE_OF_CONDUCT.md) file to see how can you do your button and how this repository works. <br />

And if you **open** an issue or a pull request you must **assign** me the issue and **mention** me.
## Realeses Features :clipboard:
You can see the features of each realese [here](https://github.com/Ruben35/Icons-unFold-Rainmeter/blob/master/REALESES_FEATURES.md).
## Authors and Credits :book:
* The original idea of the unFold skins is of [DevilRev](https://www.deviantart.com/devilrev).
* The buttons on this repository were developed by:
    - [Ruben35](https://github.com/Ruben35) Owner of this repository.
    - [ItsIgnacioPortal (aka PinkDev1)](https://github.com/ItsIgnacioPortal) Contributor.
    - [feedmes1eep](https://github.com/feedmes1eep) Contributor.
## License :page_with_curl:
All the content of this project is under the GNU General Public License v2.0 - look the [LICENSE](https://github.com/Ruben35/Icons-unFold-Rainmeter/blob/master/LICENSE) file for more details.
