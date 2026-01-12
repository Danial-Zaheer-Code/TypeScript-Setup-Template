# Introduction
This repo is a template for starting a Simple TypeScript Project right away.

## Contains
- Local TypeScript Compiler.
- Jest for testing purposes.
- Usage Examples.

# How to Use
## Prequisites
- A Github account.
- Git installed on your machine and configured with your Github account.
- Node installed.

## Clone the project
- Go to the folder where you want to clone it.
- Open git bash in that folder.
- Write this command:
  ```bash
  git clone https://github.com/Danial-Zaheer-Code/TypeScript-Setup-Template.git

- The folder will be cloned
- You can also download the zip file.

## Usage

- Open the cloned folder in VS Code or just your file explorer.
- Open command prompt in this folder.
- Write this command to install all packages.
  ```bash
  npm install

### Compilation
- Open the src folder.
- You will see two files
  1. HellowWorld.ts
  2. sum.ts
- From root folder of repo run this command:
  ```bash
  npx tsc

- Both files will be compiled and put into ./dist/ folder.


### Run the code
- From root folder of repo run this command:
  ```bash
  node ./dist/HelloWorld.js
- You will see Hello World printed on the console.

### Run Tests
- Open the __tests__ folder.
- You will see one file
  1. sum.test.ts
- From root folder of repo run this command:
  ```bash
  npm test

- The test file will run and show the result of test on the console.


# Note
- Place all the typescript file inside src folder and all of them will be compiled in dist folder with the same folder structure as inside src folder.
- Place all the test file inside __tests__ folder and each test file name should end with .test.ts.

# To use it for your project
- Run this command from the root folder of cloned project using command prompt:
  ```bash
  rmdir /s /q .git
- This will delete the .git folder if it exists.
- Change the name of the cloned folder to your project.
- Now, push it to your project repo on Github.
- Change the name of project and repo urls inside the package.json. 


