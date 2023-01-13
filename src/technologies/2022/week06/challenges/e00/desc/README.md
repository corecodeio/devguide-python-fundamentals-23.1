# Development environment

## Description

Javascript is an interpreter language, meaning we need some sort of program (Interpreter) to translate the code we made into machine code (the language the computer understands). By now we know two interpreters, the one inside every browser and the one inside Node, this makes us possible to execute Javascript scripts

As developers, we try to have environments in which we feel comfortable creating those scripts, in this guide, we will show you three different environments in which you can work your scripts. Most of the exercises you will be doing in the Bootcamp regarding Javascript will already provide you with a development environment, you could write directly your solution in the given environment, but we believe that it is better to first try the exercise in a personal environment and then pass it to the environment given by the exercise

## Environments

1. [Web](#1-web)
2. [Browser](#2-browser)
3. [Local](#3-local)

## 1. Web

For web development environment we like this simple environment called [JS Bin](https://jsbin.com/?js,console), by default we like the configuration that has the section for the Javascript code and the section for the output (the console)

To execute your code, you will just need to click on `Run`, remember that in order for you to interact with the output section, you will need to output the variable or result you want to see using the console.log() expression

For example, if you were to have this code, and you wanted to know the value of `y`, if you click the `Run` button, nothing will happen, because there is no interaction with the output section

![web_editor00](../../../assets/web_editor00.gif 'web_editor00')

Now, if you use the `console.log` expression to output the variable `y`, you will have the value of that variable in the output section when clicking the `Run` button

![web_editor01](../../../assets/web_editor01.gif 'web_editor01')

⚠️ Remember that `console.log` is used to see the output but all the challenges will not require that statement to be submitted, they usually check for a return value, or sometimes you add the correct expressions

⚠️ The advantage of using a web approach is that you don’t need to create new files or install anything, but that also gives us disadvantages because we don’t have files, our programs are temporal, and there is a risk that after closing the web page, you will lose your code

## 2. Browser

The browser approach is the most simple local environment, you will be using your favorite browser and a text editor to test your scripts.

For the browser, feel free to use your favorite browser (Chrome, Firefox, Edge, Opera…)
For the Text editor, we recommend you not use your computer's default editor, instead select one from the following list:

1. [Visual Studio Code](https://code.visualstudio.com/)
2. [Sublime Text](https://www.sublimetext.com/)
3. [Notepad++](https://notepad-plus-plus.org/)
4. [Atom](https://atom.io/)

During the Bootcamp, we will be using Visual Studio Code, but if you already use a different text editor or you liked another editor, do not worry, you can use a different editor than the one we will be using in the Bootcamp

After selecting your `browser` and `text editor` if you don’t have it installed on your computer, proceed to install each of the options you selected.

Now that you have all the requirements installed on your computer, we will proceed to execute an example of how you will be creating and executing a Javascript script, for this example I will use `Edge` as my preferred browser and `Visual Studio Code` as my preferred text editor

The first thing that we need to do is to open the text editor, as you can see this is the default window of Visual Studio Code

![browser_setup00](../../../assets/browser_setup00.png 'browser_setup00')

The second thing that we need to do is to create two files, one HTML file, and one Javascript file, the HTML file will be the required file for the browser to read and execute the Javascript file, remember that the execution of a Javascript script on the browser depends on an HTML file, for more details on how the browser executes a Javascript file from reading an HTML file, refer to [this discussion](https://stackoverflow.com/questions/4243055/how-do-browsers-handle-javascript)

Here is how we create the HTML file, we create a new file and then we paste the basic structure of an HTML file, (you can find the basic structure above this paragraph)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Example</title>
  </head>
  <body>
    <h1>This is a title</h1>
  </body>
</html>
```

Remember to save the HTML file with the `html` extension in a place where you can find it later, don't worry about the name, it can be anything you like

⚠️ To save the file you can use the `ctl + s` or `command + s` keys depending on your operative system

![browser_setup01](../../../assets/browser_setup01.gif 'browser_setup01')

After creating the HTML file, we will create the Javascript file, for now, this will be an empty file, remember that the Javascript file needs to be saved in the same location where we save the previous `html` file

Remember to save the Javascript file with the `js` extension in a place where you can find it later, don't worry about the name, it can be anything you like

⚠️ To save the file you can use the `ctl + s` or `command + s` keys depending on your operative system

![browser_setup02](../../../assets/browser_setup02.gif 'browser_setup02')

If we open the `html` file, the file will be open on the browser, and a white page with the `This is a title` text will be shown on the browser, this is the HTML file interpreted by the browser, if you take a look on the simple structure that we paste on the HTML file, there was a statement with the `This is a title` phrase, each of the tags (`<head>`, `<body>`, `<h1>` ...) are compiled by the browser and tranformed in a friendly way for the user (that is how web pages works)

![browser_setup03](../../../assets/browser_setup03.gif 'browser_setup03')

Ok, but we are focused on executing Javascript code not on creating a web page using HTML, how does the browser knows how to execute the Javascript code that we want?

For the browser to know which Javascript code to execute, we have to explicitly tell it where the code to execute is by means of a special tag, this special tag is called `<script>` this tag is used in the HTML file to tell the browser the address of the script, in this case, the address will be local (in our computer) but usually this address is the address of some server that has the script,

This is how the HTML file will look like after adding the `<script>` tag

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Example</title>
  </head>
  <body>
    <h1>This is a title</h1>
    <script src="example.js"></script>
  </body>
</html>
```

![browser_setup04](../../../assets/browser_setup04.gif 'browser_setup04')

⚠️ After editing the file, remember to save the file, you can use the `ctl + s` or `command + s` keys depending on your operative system to save the file

For the browser to read again the file, we need to refresh the page, let's check what happen if we refresh the page

![browser_setup05](../../../assets/browser_setup05.gif 'browser_setup05')

Nothing…, well this is because we are not looking where we should. If we want to check the results of a Javascript script we should look for the output section, in other words… we need to check the console, for that, every browser gives us a tool called `Developer Tools`, there are different ways to open the `Developer Tools` depending on your browser, but the easiest way to do it, is to hit right click and select inspect inside the web page. After that, the `Developer Tools` will be shown, and from there we can search the `console`

![browser_setup06](../../../assets/browser_setup06.gif 'browser_setup06')

Well… there is nothing there two…, but this is because the Javascript file is empty, let’s add some code and check again, you can find the example code above this paragraph. For this example, we want to know the value of `x` after doing all those operations

```javascript
let x = 81;

x = x / 2;

x++;
```

⚠️ After editing the file, remember to save the file, you can use the `ctl + s` or `command + s` keys depending on your operative system to save the file

⚠️ To check the result, you need to refresh the web page

![browser_setup07](../../../assets/browser_setup07.gif 'browser_setup07')

Again there is no result…, but we know why, don’t we? this is because we are missing the way to show the output, for the console to show something we need to add the statement to show in the console, this statement is the `console.log`, above this paragraph, you will find the final code that will show the value of `x` in the `console`

```javascript
let x = 81;

x = x / 2;

x++;

console.log(x);
```

If we refresh, we will find the value on the console

![browser_setup08](../../../assets/browser_setup08.gif 'browser_setup08')

From now on, you can use this method to test your challenges, just copy the code of the challenge and hit refresh. You can re-use these two files (HTML & Javascript) for all the challenges or create two new files for each of the challenges to test, you decide

## 3. Local

For this method, you will need to installed the following programs:

1. [Visual Studio Code](https://code.visualstudio.com/)
2. [Node](https://nodejs.org/en/) ⚠️Select the `LTS` option

Once the programs are downloaded, you need to install them. For installation, you can leave the default settings (click next and accept on all options)

Visual Studio Code will be the editor to use to write our scripts in Javascript, and Node will be the environment that will have the interpreter that will help us execute our code. Node will be doing the work in the background and we will not realize for the moment that we are using it

The following steps should only be performed once, when you finish them you can use the way to execute Javascript as shown at the end of the guide

The first thing to do will be to start Visual Studio Code, once the Visual Studio Code window is opened, you must select the 'Extensions' option. A search bar will be displayed at the top right, within this bar type the following name: `Quokka.js` and select install

![local_setup00](../../../assets/local_setup00.gif 'local_setup00')

Quokka.js is an extension of Visual Studio Code that allows us to execute Javascript using Node directly from the text editor, without the need for a browser. You must bear in mind that this is only used for development since in production the code is executed by the browser or the backend server (using Node or another runtime)

At the end of this process, you can start using Quokka.js for all the challenges to be performed, we will proceed to show an example that how to use it

The example will show how to start a file with Quokka.js, for this, you will see that a small pop-up window opens where you can write and select the Quokka option.js and the language to interpret (Javascript) in order to access this small pop-up window shown in the video, you must press the following key combination according to your operating system

Windows / Linux: `Ctrl+ Shift + P`
macOS: `Cmd + Shift + P`

![local_setup01](../../../assets/local_setup01.gif 'local_setup01')

As you can see there is no need to use `console.log` to get the value of a variable, and also you get feedback if you have to type the syntax of an instruction in the wrong way. For more information on how to use Quokka.js, refer to this [link](https://quokkajs.com/docs/#getting-started)
