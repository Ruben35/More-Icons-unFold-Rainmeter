![GitHub All Releases](https://img.shields.io/github/downloads/Ruben35/Icons-unFold-Rainmeter/total.svg?color=informational) ![Github All Releases](https://img.shields.io/badge/license-GNU%20GPLv2-informational.svg) [![HitCount](http://hits.dwyl.io/Ruben35/https://github.com/Ruben35/Icons-unFold-Rainmeter.svg)](http://hits.dwyl.io/Ruben35/https://github.com/Ruben35/Icons-unFold-Rainmeter)

# _Collection of animated_ **_„unFold”_** _buttons for **Rainmeter**_ 
# &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**➕**
#  **_„reFold”_** -  _the animated button creation framework for **Rainmeter**_
### In this repository, you will find a variety of icons of the **unFold** type for **Rainmeter**.

## Table of Contents
1. [What are the **„unFold”** buttons?](#1-what-are-the-unfold-buttons)
2. [Prerequisites](#2-prerequisites)
3. [Installation](#3-installation)
4. [How to contribute?](#4-how-to-contribute)
5. [reFold](#5-refold-📰)
6. [Changelog](#6-changelog)
7. [Authors and Credits](#7-authors-and-credits)
8. [License](#8-license)

## 1. What are the unFold buttons?
 ### The **unFold** buttons, functionally are the same as shortcuts you can find on every desktop.

 ### &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; _**The point is... They're not boring!**_  <br><br>
  - ### &nbsp; They unfold beautifully &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; <sub>**_-  when You hover the cursor over them!_**</sub>
    - ### &nbsp; Their animation is so slick &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; <sub>**-  _they maintain a minimalistic vibe!_**</sub>
      - ### &nbsp; High contrast elegant design &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  <sub>**-  _gives them a very classy look!_**</sub>
        - ### &nbsp; They complement any desktop &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; <sub>**_- and make it A LOT cooler!_**</sub><br><br><br><br>
          ### &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; And the cherry on top is...
             ### &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp;   **_They're fully customisable!_**<br><br><br>
---
### _Example of desktop design making use of unFold buttons:_
![Example of Desktop](https://user-images.githubusercontent.com/30848819/50526747-ca391480-0aa9-11e9-832c-b93dbca7e8d7.jpg)
---
###### Example of a button once it **unfolds**:
![Example of Button](https://user-images.githubusercontent.com/30848819/50526744-bdb4bc00-0aa9-11e9-8cbb-c4e4d81813f8.jpg)

## 2. Prerequisites
Before you can use **„unFold”** buttons to make Your desktop all shiny, You'll need 2 very simple things:
* [Rainmeter](https://www.rainmeter.net) (version 4.2.0 or higher) installed on your PC. 
* A tiny little bit of free space on your drive (perhaps 10MB)

If you'd like to see some more examples of **unFold** buttons,  
I very much recommend taking a look at this [DeviantArt gallery](https://www.deviantart.com/devilrev/art/unFold-A-Launcher-618503449) made by [DevilRev](https://www.deviantart.com/devilrev),  
who has originally initiated the idea of **unFold** buttons.

## 3. Installation

There are **2** easy ways to install the buttons for use within RainMeter:

**1. The simplest way:**

- Head to the [releases](https://github.com/Ruben35/More-Icons-unFold-Rainmeter/releases) page and **download** the latest **_.rmskin_** binary
- Once the file is downloaded, run the file by clicking it twice and proceed with the installation wizard

**2. The oldschool way:**
- Download this repository by clicking the **green "code" button** and selecting **"download zip"**.
   - _Alternatively you can clone the repository using ```git clone``` directly via terminal_
- Unpack the zip
- Copy the unpacked folder to the Skins folder located within the Rainmeter folder, in my case the Path was:  
**C:\Users\userName\Documents\Rainmeter\Skins**  
Exact path can be different for you but this is all that matters:  
**Rainmeter\Skins\PUT_THE_FOLDER_HERE**

## 4. How to contribute?
If You'd like to contribute to this repository you can:
* **Open** issues in order to **give** me suggestions for new buttons.
* **Open** issues in order to **report** a bug.
* **Star** this repository.
* **Fork** this repository and **make** your own buttons, then **create** a pull request.

If You consider a direct contribution,
please take a look at the [CONTRIBUTION GUIDELINES](CONTRIBUTION_GUIDELINES.md) and make sure to respect the [CODE OF CONDUCT](CODE_OF_CONDUCT.md).

## 5. reFold 📰
_reFold is a modified version of unFold where everything (except the icon) can be defined in the "ini" file._
This allows you to have different color text, background, etc., with code adjustments alone,
making creation of new buttons way easier!

### reFold Configuration 
To use reFold, follow these steps:

1. Download the repository and make copies of the `reFold-template_Left` or `reFold-template_Right`.
2. Download a square .png of the app logo you're looking to create a button for, to your drive(you can find this kind of .png on the web).
3. Place the .png file in the **@Resources** folder.
4. In the main directory create a folder and name it exactly the same as the app you'd like to create a button for.
For example If you'd like to create a button for **Roblox**, name the folder **Roblox**.
In this folder depending on the style of button or buttons you're going to make, create subfolder(s):
- "Black" (for buttons with black background and white text and logo)
- "White" (for buttons with white background and black text and logo)
- "Transparent" (for buttons with no background)
5. Paste the template **"ini"** file into one of the folders.
3. Open the "ini" file with a text editor and scroll to the [Variables] section.
4. Configure the file:

- `Width``: 
  - Defines width of the button when collapsed.
- `Height`: 
  - Defines height of the button when collapsed.
- `maxWidth`: 
  - Defines size of the button once **unFolded**.
- `bgColor`:
  - Defines the background color and opacity. Opacity should be at least 1.
- `iconColor`:
  - Defines the icon color.
- `iconPath`:
  - Defines path to the icon. Place icons in the "Images" folder in the unFold skin.
- `iconSize`:
  - Defines icon size.
- `textColor`:
  - Defines color of text.
- `textString`:
  - Defines text to be displayed on the button.
- `textFont`:
  - Defines font face. Windows installed fonts and fonts in "Fonts" folder are valid.
- `textWeight`:
  - Defines text weight. 100 = thin, 900 = bold.
- `textSize`:
  - Defines text size.
- `application`:
  - Change this to match the path to the application the button should run. Please see below for more information about syntax.

### application syntax
- The simplest way to set the application parameter correctly is to put the full path to your application in square brackets and double quotes. Eg:\
```v
application = ["C:\Program Files (x86)\Google\Chrome\Application\chrome.exe"]
application = ["C:\Users\Username\Documents\important.doc"]
```

- If your application is already available via your ```PATH``` environment variable, you can simply use:
```v
application = ["chrome.exe"]
```

- If you'd like to open a program with additional paramaters, that can be accomplished too:
```v
application = !Execute ["chrome.exe" rainmeter.net]

application = !Execute ["chrome.exe" --incognito rainmeter.net]
```

- You can also launch multiple executables at once by placing multiple actions in consecutive square brackets 
```v
application= !Execute ["chrome.exe" rainmeter.net]["Calc.exe"]
```

### **[In case of any trouble with configuration, please take a look at the code of buttons that were made using the reFold scheme](./Vivaldi/Black/Vivaldi%20Right.ini)**

## 6. Changelog
You can see the features of each release [here](CHANGELOG.md).

## 7. Authors and Credits
* The original idea of the unFold skins by [**DevilRev**](https://www.deviantart.com/devilrev).
* Owner of this repository [**Ruben35**](https://github.com/Ruben35).
* Kudos to the kind souls who decided to contribute to this project:
    - [**ItsIgnacioPortal (aka PinkDev1)**](https://github.com/ItsIgnacioPortal) for code contributions.
    - [**feedmes1eep**](https://github.com/feedmes1eep) for code contributions.
    - [**Veexer**](https://github.com/veexer) for code contributions and making this **readme.md** fun.
    - [**Shades84**](https://github.com/Shades84) for the **reFold** project and making the buttons modular!


## 8. License
All the content of this project is under the GNU General Public License v2.0 - see the [LICENSE](LICENSE) file for more details.

---
### _[Back to the Top](#top)_



