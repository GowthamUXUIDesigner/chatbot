# Gowtham <image width="30" height="30" src="https://user-images.githubusercontent.com/69076784/236995719-a3e9e978-f19d-4466-abd9-b8a59c8de0f9.png">
###### A Chatbot with a GUI made for you to get News Headlines, Weather, Stocks, Wiki and more....

Kindly consider starring this repository if you like the program :-)

## Table Of Contents
- [WHAT'S NEW?](#whats-new)
- [Screenshots of Gowtham](#screenshots-of-gowtham)
- [Introduction to Gowtham](#introduction-to-gowtham)
- [How to run Gowtham](#how-to-run-gowtham)
- [How does Gowtham store info](#how-does-gowtham-store-info-and-is-it-safe)
- [What Are The APIs should I subscribe to?](#what-are-the-apis-should-i-subscribe-to)
- [Examples of Gowtham commands](#some-examples-of-gowtham-commands)
- [License](#license)


## WHAT'S NEW?
Here at Epicalable we are committed in keeping Gowthamup-to-date and up-to-speed with the growing tech solutions and algorithms. Hence this new commit includes:
```Updates In This Commit:-
Update Highlights:-
1. Bug fixes and UX enhancements.

Monthly Maintanance Updates:-
1. Minor updates to README.md
2. Standardization of different definitions.
3. Monthly Code checks, updates and Maintanence to continue supporting python 3.11.3.

Code Checks Manifest:-
All Checks Status: ✅
-----------------------------------------
Code Integrity Checks: ✅
GUI Stability Checks: ✅
Code-GUI Integration Checks: ✅
(All evaluations are done by the R&D Department)


```
Keep updated to what's happening on this repository by clicking the 'Star' and 'Watch' button on the top right corner of this webpage.



## Screenshots of Gowtham
##### Graphical User Interface :-

<img src="https://user-images.githubusercontent.com/69076784/180637424-8d2737c9-ead7-4d65-a8e8-a2c36d9474e8.png" width="100" height="60"> <img src="https://user-images.githubusercontent.com/69076784/232394556-eff71901-0926-42e3-9161-7469759c3c7c.png" width="100" height="60"> <img src="https://user-images.githubusercontent.com/69076784/206891927-da7d86b8-e3df-4922-a887-7be46cc94070.png" width="100" height="60"> <img src="https://user-images.githubusercontent.com/69076784/210161820-44109b56-a2bf-4410-a90d-a3ded829dfb2.png" width="100" height="60">

##### Code Workspace (VSCode + One Dark Pro + Pylance) :-
<img src="https://user-images.githubusercontent.com/69076784/233782216-154d7e53-fa02-4770-ab9a-dec5f923cbee.png" width="100" height="60"> <img src="https://user-images.githubusercontent.com/69076784/233782218-b09d765c-e7db-4e31-a213-a00b60953b0e.png" width="100" height="60">  

###### Note: As of 1 May all of Epicalable Systems have been upgraded to windows 11.


## Introduction to Gowtham?
Gowtham was started in 2019 as an Command-Line Interface Application in C++ and after careful consideration was shifted to Python during 2020 due to some limitations.  
Gowtham has been constantly evolved over the years to where it is now, integrated with a GUI and new features being added every month. While our staffs in Epicalable are constantly fixing bugs and closing issues behind the scenes.  
So what does Gowtham do? Well JARVIS is known as a chatbot it also can get news, weather, get location, send emails, flight info, stock prices, wikipedia and some more cool features sprinkled in by our programmers.



## How to run Gowtham?
To run Gowtham, user are to open up the JarvisGUI.py file and 'pip' download the 3rd party packages so users can run Jarvis successfully without any problems.  
Users facing any issues can open up an issue at the [Issues](https://github.com/Epicalable/JARVIS/issues) section of JARVIS Github Page and can expext us to rectify it ASAP.  

In order for Gowtham to work at full capacity a few 3rd party python packages will be required to be installed:
1. pip install PySimpleGUI
2. pip install requests
3. pip install beautifulsoup4
4. pip install wikipedia
5. pip install geocoder



## How does Gowtham store info and is it safe?
Yes, Your info will be safe since it will be stored locally on your personal computer. Gowtham stores these info into 3 main sources.

1. Response-Intents: Stored in Jarintents file used by Gowtham to check your input with tags and provide the appropriate output for the user. Head to Jarindent.json to take a look.

2. Info-Intents: Stored in Jarsettings file used by gowtham to access Api keys, User Name and location for data retrieval and also to adjust the output and input screen sizes. You can access these by heading to settings in the menu.  

3. Audit-Indents: Stored in the Jaraudit file used by Gowtham to store user input/output logs, system retrival logs and fallback errors in your computer. You can access them by heading to ChatLogs in the menu.

All CRITICAL INFO REGARDING the USER will be STORED IN your PERSONAL COMPUTER and NOT on the INTERNET.



## What Are The APIs should I subscribe to?
When completed installing, by default you can chat with Gowtham using temporary APIs provided to you. But if you want it to be personalised then it is best to activate the API. To do that you will need to head to:

1. https://newsapi.org/ : For Live News, Morning Briefings and News Headlines.

2. https://openweathermap.org/ : For current Weather information.

Both websites once registered will provide you an API key, Users should then copy the API key and paste it in the respective bars in the settings menu.



## Some examples of Gowtham commands.
To make Gowtham respond Users will need to enter a Command in the input bar and then Gowtham will scan for keywords and provide an answer or information.

Here is a sample list of available Commands:
* Hello
* How are you
* Are you fine
* Are you real
* Tell me the time
* News on [your input]--  
    Ex. News on Github.
* Get me news headlines
* Send an email
* Wikipedia [Query]--  
    Ex. Wikipedia github.
* Who is [Query] / What is [Query]--  
    NOTE: Gowtham will get answer from Wikipedia.
* Get me stock price--  
    NOTE: Stock abbreviations EX."TSLA AAPL MSFT" will be in Setting under "StockPrice".
* Track flight <Flight Number>  
    NOTE: Number of Flight like SQ 11, SQ 305, SQ 335, SQ 23   
    Ex. Track flight SQ 242
* Goodbye --  
    NOTE: Command to quit Gowtham.



## License  
[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/Epicalable/)  

IMPORTANT NOTE: Any User who are willing to Share or Re-Distribute JARVIS are kindly advised to:

1. A reference to us by keeping a "(C) Epicalable" text in the 'Modified program' such as keeping it in the settings menu, about or help page.

2. A link to this repository from the user's 'Modified program' README file. 

It will be helpful for us as users will know it's original source and about our startup.
Please also refer to LICENSE file for clarifications.  
Thank you for your kind cooperation :-)


Version 1.3  
Gowtham Copyright (C) Epicalable 2024 
All Rights Reserved.
