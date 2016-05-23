Introduction to UnrealEngine using CPP

> Note 1: This tutorial is being developed using UnrealEngine 4.11.*

<!-- TOC depthFrom:2 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [1 Introduction](#1-introduction)
	- [1.1 Requirements](#11-requirements)
- [2 Running C++ code](#2-running-c-code)
	- [2.1 Windows](#21-windows)
	- [2.2 Mac](#22-mac)
	- [1.2.1 Creating a project](#121-creating-a-project)

<!-- /TOC -->

## 1 Introduction

UnrealEngine 4 provides two ways to create a game:

1. [Blueprint](https://docs.unrealengine.com/latest/INT/Engine/Blueprints/)
2. [Coding with C++](https://docs.unrealengine.com/latest/INT/Programming/)

A tutorial on how to use UnrealEngine 4 using Blueprint is given here -> [https://blog.gollahalli.me/2016/05/10/introduction-to-unrealengine-4/](https://blog.gollahalli.me/2016/05/10/introduction-to-unrealengine-4/)

This tutorial focuses on how to use the C++ language with the UnrealEngine.

### 1.1 Requirements

1. Basic knowledge in Object Oriented Programming
2. A Mac with XCode or Windows 7+ with [Visual Studio 2015 Community](https://www.visualstudio.com/)
3. [UnrealEngine](https://www.unrealengine.com/)

## 2 Running C++ code

Depending on the operating system you use, there are different ways of running or compiling a C++ program. By default, UnrealEngine creates a XCode project on Mac and Visual Studio project on Windows.

### 2.1 Windows


### 2.2 Mac

* Open `XCode.app`, then click on `Create a new XCode project`

<p align="center"><img src="https://raw.githubusercontent.com/akshaybabloo/UnrealEngine-and-CPP/master/Screenshots/xcode_main.png" alt="New Project" width="700"></p>

* Under `OS X` click on `Application -> Command Line Tool` and finally click  <kbd>Next</kbd>

<p align="center"><img src="https://raw.githubusercontent.com/akshaybabloo/UnrealEngine-and-CPP/master/Screenshots/xcode_new_project.png" alt="New Project" width="700"></p>

* Next, fill in the details and click <kbd>Next</kbd>.

<p align="center"><img src="https://raw.githubusercontent.com/akshaybabloo/UnrealEngine-and-CPP/master/Screenshots/xcode_project_name.png" alt="New Project" width="700"></p>

* This will open a pop-up asking you to choose a destination, once selected, click <kbd>Create</kbd>.

* A new project wind is opened that looks like this:

<p align="center"><img src="https://raw.githubusercontent.com/akshaybabloo/UnrealEngine-and-CPP/master/Screenshots/xcode_project_window.png" alt="New Project" width="700"></p>

```cpp
//
//  main.cpp
//  HelloWorld
//
//  Created by Akshay Raj Gollahalli on 20/05/16.
//  Copyright © 2016 Akshay Raj Gollahalli. All rights reserved.
//

#include <iostream>

int main(int argc, const char * argv[]) {
    std::cout << "Hello, World!\n";
    return 0;
}
```

**Running the code**

To run the code do the following, from the menu bar click on `Product -> Run` or <kbd>cmd</kbd>+<kbd>R</kbd>

<p align="center"><img src="https://raw.githubusercontent.com/akshaybabloo/UnrealEngine-and-CPP/master/Screenshots/xcode_run.png" alt="New Project" width="700"></p>

If you are running `XCode` for the first time, you might have to enable developer mode on your Mac.

<p align="center"><img src="https://raw.githubusercontent.com/akshaybabloo/UnrealEngine-and-CPP/master/Screenshots/xcode_developer_mode.png" alt="New Project" width="700"></p>

Click on `Enable`, this will ask you for your username and password for authentication. Once authenticated, you will find the result at the bottom of the `XCode`.

<p align="center"><img src="https://raw.githubusercontent.com/akshaybabloo/UnrealEngine-and-CPP/master/Screenshots/xcode_result.png" alt="New Project" width="700"></p>


### 1.2.1 Creating a project

To create a project, open the `Epic Game Launcher`. There are two ways to launch `UnrealEngine`

1. Click on the big button on the left side of the launcher, that says `Launch`.
2. Or, go to `Library`, under `Engine Versions` click on `Launch`.

<p align="center"><img src="https://raw.githubusercontent.com/akshaybabloo/UnrealEngine-and-CPP/master/Screenshots/epic_launcher.png" alt="New Project" width="700"></p>

Once the `UnrealEngine` is up and running, you would have to create a project, to do that, click on `C++` tab, under that click on `Basic Code`, then click on `Starter Content` and select `No Starter Content` then finally click on `Create Project`.

 <p align="center"><img src="https://raw.githubusercontent.com/akshaybabloo/UnrealEngine-and-CPP/master/Screenshots/ue_project.png" alt="New Project" width="700"></p>
