# :electric_plug: figwalk

<b>Figma plugin template</b>
<br />

<!--
Below are the steps to get your plugin running. You can also find instructions at:

https://www.figma.com/plugin-docs/setup/

This plugin template uses Typescript and NPM, two standard tools in creating JavaScript applications.

First, download Node.js which comes with NPM. This will allow you to install TypeScript and other
libraries. You can find the download link here:

https://nodejs.org/en/download/

Next, install TypeScript using the command:
```
npm install --save-dev typescript
```
Finally, in the directory of your plugin, get the latest type definitions for the plugin API by running:
```
npm install --save-dev @figma/plugin-typings
```
If you are familiar with JavaScript, TypeScript will look very familiar. In fact, valid JavaScript code
is already valid Typescript code.

TypeScript adds type annotations to variables. This allows code editors such as Visual Studio Code
to provide information about the Figma API while you are writing code, as well as help catch bugs
you previously didn't notice.

For more information, visit https://www.typescriptlang.org/

Using TypeScript requires a compiler to convert TypeScript (code.ts) into JavaScript (code.js)
for the browser to run.

We recommend writing TypeScript code using Visual Studio code:

1. Download Visual Studio Code if you haven't already: https://code.visualstudio.com/.
2. Open this directory in Visual Studio Code.
3. Compile TypeScript to JavaScript: Run the "Terminal > Run Build Task..." menu item,
   then select "tsc: watch - tsconfig.json". You will have to do this again every time
   you reopen Visual Studio Code.

That's it! Visual Studio Code will regenerate the JavaScript file every time you save.
-->

## :memo: Prerequisites
Install the [Figma desktop app](https://www.figma.com/downloads/) and [node.js](https://nodejs.org/en/download/)
\
\
Clone the project repo
```
$ git clone https://github.com/sethvm/figwalk.git
```
Install the project dependencies
```
$ cd figwalk
$ npm install
```
Compile the plugin template
```
$ npm run build
```

## :computer: Running in Figma
 - In the Figma desktop app, Navigate to the `Plugins` menu via the user dropdown
 - Under `In development`, open the menu and select `Import plugin from manifest...`
 - Select the `manifest.json` file in the project root folder
 - Open any Figma board and load the plugin from the `Plugins > Development` menu

## :stars: To-Do
 - Implement React tooling
 - Instruction screenshots
 