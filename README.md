![GitHub All Releases](https://img.shields.io/github/downloads/Ruben35/Icons-unFold-Rainmeter/total.svg?color=informational) ![Github All Releases](https://img.shields.io/badge/license-GNU%20GPLv2-informational.svg) [![HitCount](http://hits.dwyl.io/Ruben35/https://github.com/Ruben35/Icons-unFold-Rainmeter.svg)](http://hits.dwyl.io/Ruben35/https://github.com/Ruben35/Icons-unFold-Rainmeter)

# More Icons Rainmeter unFold
In this repository, you will find a variety of icons of the **unFold** type for **Rainmeter**.

## Table of Contents
1. [What are the unFold skins?](#what-are-the-unfold-skins)
2. [Pre-requirements](#pre-requirements)
3. [Installation](#installation)
4. [How to contribute?](#how-to-contribute)
5. [Releases Features](#releases-features)
6. [Authors and Credits](#authors-and-credits)
7. [License](#license)

## 1. What are the unFold skins?
The **unFold** skins are buttons that You can add to your desktop and use them as way better looking shortcuts.
They have a gorgeous design and **unFold** themselves when You hover over them!

###### Example of desktop design making use of unFold buttons:
![Example of Desktop](https://user-images.githubusercontent.com/30848819/50526747-ca391480-0aa9-11e9-832c-b93dbca7e8d7.jpg)

###### Example of a button once it **unfolds**:
![Example of Button](https://user-images.githubusercontent.com/30848819/50526744-bdb4bc00-0aa9-11e9-8cbb-c4e4d81813f8.jpg)

## 2. Pre-requirements
Before you can use **unFold** buttons to make Your desktop all shiny, You'll need 2 very simple things:
* [Rainmeter](https://www.rainmeter.net) (version 4.2.0 or higher) installed on your PC. 
* A tiny little bit of free space on your drive (perhaps 10MB)

If you'd like to see some more examples of **unFold** buttons,
I very much recommend taking a look at this [DeviantArt gallery](https://www.deviantart.com/devilrev/art/unFold-A-Launcher-618503449) made by [DevilRev](https://www.deviantart.com/devilrev),
who has originally initiated the idea of **unFold** buttons.

## 3. Installation

There are 2 easy ways to install the buttons for use within RainMeter:

**The simplest way:**

1. Head to the [releases](https://github.com/Ruben35/Icons-unFold-Rainmeter/releases) page and **download** the latest **_.rmskin_** binary
2. Once the file is downloaded, run the file by clicking it twice and proceed with the installation wizard

**The oldschool way:**
1. Download this repository by clicking the **green "code" button** and selecting **"download zip"**.
- Alternatively you can clone the repository using 'git clone' directly via terminal
2. Unpack the zip
3. Copy the unpacked folder to the Skins folder located within the Rainmeter folder, in my case the Path was:
C:\Users\userName\Documents\Rainmeter\Skins
Exact path can be different for you but this is all that matters:
**\Rainmeter\Skins\PUT_THE_FOLDER_HERE**

## 4. How to contribute?
If You'd like to contribute to this repository you can:
* **Open** issues in order to **give** me suggestions for new buttons.
* **Open** issues in order to **report** a bug.
* **Star** this repository.
* **Fork** this repository and **make** your own buttons, then **create** a pull request.

If You consider a direct contribution,
please take a look at the [CONTRIBUTION](https://github.com/Ruben35/Icons-unFold-Rainmeter/blob/master/CONTRIBUTING.md) guidelines and make sure to respect the [CODE_OF_CONDUCT](https://github.com/Ruben35/Icons-unFold-Rainmeter/blob/master/CODE_OF_CONDUCT.md).

## 5. Releases Features
You can see the features of each release [here](https://github.com/Ruben35/Icons-unFold-Rainmeter/blob/master/RELEASES_FEATURES.md).

## 6. Authors and Credits
* The original idea of the unFold skins by **[DevilRev]**(https://www.deviantart.com/devilrev).
* Owner of this repository **[Ruben35]**(https://github.com/Ruben35).
* Kudos to the kind souls who decided to contribute to this project:
    - **[ItsIgnacioPortal (aka PinkDev1)]**(https://github.com/ItsIgnacioPortal) for code contributions.
    - **[feedmes1eep]**(https://github.com/feedmes1eep) for code contributions.
    - **[Veexer]**(https://github.com/veexer) for code contributions and taking the time to make this **readme.md** fun and easy.
    - **[Shades84]**(https://github.com/Shades84) for the **reFold** project and making the buttons modular!

## 7. License
All the content of this project is under the GNU General Public License v2.0 - see the [LICENSE](https://github.com/Ruben35/Icons-unFold-Rainmeter/blob/master/LICENSE) file for more details.

## reFold 📰
_reFold is a modified version of unFold where everything (except the icon) can be defined in the "ini" file._
This allows you to have different color text, background, etc., with code adjustments alone,
making creation of new buttons way easier!

### reFold Configuration 
To use reFold, follow these steps:

1. Download the repository and make copies of the `reFold-template_Left` or `reFold-template_Right`.
2. Download a square .png of the app logo you're looking to create a button for, to your drive(you can find this kind of .png on the web).
3. Place the .png file in the **@Resources\reFold** path inside of **Rainmeter/Skins**
4. In the main directory create a folder and name it exactly the same as the app you'd like to create a button for.
For example If you'd like to create a button for **Roblox**, name the folder **Roblox**.
In this folder depending on the style of button or buttons you're going to make, create subfolder(s):
- "Black" (for buttons with black background and white text and logo)
- "White" (for buttons with white background and black text and logo)
- "Transparent" (for buttons with no background)
5. Paste the template **"ini"** file into one of the folders
3. Open the "ini" file with a text editor and scroll to the [Variables] section.
4. Configure the file:

- `Width`, `Height`, `maxWidth`: Define the collapsed and expanded size of the button.
- `bgColor`: Defines the background color and opacity. Opacity should be at least 1.
- `iconColor`: Defines the icon color.
- `iconPath`: Defines path to the icon. Place icons in the "Images" folder in the unFold skin.
- `iconSize`: Defines icon size.
- `textColor`: Defines color of text.
- `textString`: Defines text to be displayed on the button.
- `textFont`: Defines font face. Windows installed fonts and fonts in "Fonts" folder are valid.
- `textWeight`: Defines text weight. 100 = thin, 900 = bold.
- `textSize`: Defines text size.
- `application`: Change this to match the path to the application the button should run. Please see below for more information about syntax.

### application syntax
The simplest way to set the application parameter correctly is to put the full path to your application in square brackets and double quotes. Eg:\
```application = ["C:\Program Files (x86)\Google\Chrome\Application\chrome.exe"]```\
```application = ["C:\Users\Username\Documents\important.doc"]```

or if your application is already available via your ```PATH``` environment variable, you can just call:\
```application = ["chrome.exe"]```

If you'd like to open a program with additional paramaters, that can be accomplished too:\
```application = !Execute ["chrome.exe" rainmeter.net]```\
```application = !Execute ["chrome.exe" --incognito rainmeter.net]```

You can also launch multiple executables at once by placing multiple actions in consecutive square brackets \
```application= !Execute ["chrome.exe" rainmeter.net]["Calc.exe"]```

## Final notes

### [In case of any trouble with configuration, please take a look at the code of buttons that were made using the reFold scheme](vivaldi/black/Vivaldi Right.ini)