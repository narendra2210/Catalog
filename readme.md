# Catalog Assignment

## Overview

This project is a simplified implementation of Secret Sharing algorithm. The goal is to reconstruct the constant term \( c \) of a polynomial using a given set of points. Each y-value in the points is encoded in different bases, and they need to be decoded before using Lagrange Interpolation to find the polynomial's constant term.

The project is written in JavaScript and can be run using Node.js in VSCode.

## Prerequisites

1. **Node.js Installed**: The project uses Node.js to run the JavaScript code.

     - If Node.js is installed, this command will print the installed version.
     - If not, you can download Node.js from [here](https://nodejs.org/) and install it.

2. **VS Code Installed**: Visual Studio Code is the recommended IDE for this project.
   - Download and install VS Code from [here](https://code.visualstudio.com/).

## Steps to Set Up and Run the Project

### 1. Create a Project Folder

- First, create a folder on your computer where you'll store the project files.
- Open VS Code, and navigate to **File > Open Folder**, and select the folder you just created.

### 2. Create a JavaScript File

- Inside the folder, create a new JavaScript file. You can name it `index.js`.
- Copy the JavaScript code (for parsing the JSON and performing Lagrange Interpolation) into `index.js`.

### 3. Create JSON Test Files

- In the same folder, create two JSON files for your test cases:
  - `testcase1.json`: Contains the first test case.
  - `testcase2.json`: Contains the second test case.

### 4. Running the Code
You can open the terminal by navigating to Terminal > New Terminal.
Run the JavaScript Code:

In the terminal, type the following command to run the script:    
bash  : node index.js

The output will be printed in the terminal.



