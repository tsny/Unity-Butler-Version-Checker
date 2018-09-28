# Unity-Butler-Version-Checker

## Description
A small script that uses a coroutine to grab the latest version of your itch.io game

## Usage
Call the GetVersions method from anywhere

#### Params
* URL: The url of your itch.io update json  
Looks like this: https://itch.io/api/1/x/wharf/latest?target=tsny/project-lonestar&channel_name=win

* caller: An optional monobehaviour if you're using UI to display the most results on a text field

* printToConsole: Whether or not the method should print the versions to console

#### Example

This example uses a in-game console by [StillWWater](https://github.com/stillwwater/command_terminal)

![Example](https://media.giphy.com/media/3ktLHWVmeMFehaCV4I/giphy.gif)
