# :electric_plug: figwalk

<b>Starter template for developing Figma plugins</b>
<br />

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
Compile the plugin
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
 