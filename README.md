Introduction to UnrealEngine using CPP

<!-- TOC depthFrom:2 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [1 Introduction](#1introduction)
	- [1.1 Requirements](#11requirements)
- [2 Running C++ code](#2runningccode)
	- [2.1 Windows](#21windows)
	- [2.2 Mac](#22mac)

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
