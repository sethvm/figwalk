# :electric_plug: FigWalk

<b>React-based starter for developing Figma plugins</b>

## :memo: Prerequisites
Install the [Figma desktop app](https://www.figma.com/downloads/) and [node.js](https://nodejs.org/en/download/)
\
\
Clone the project repo
```
git clone https://github.com/sethvm/figwalk.git
```
Install the project dependencies
```
cd figwalk
npm install
```

## :black_nib: Development
Refer to the [Figma API documentation](https://www.figma.com/developers/api) for details on developing plugins
\
\
Run the following command to build for development
```
npm run dev
```
Plugin assets are stored in the `src` directory
\
\
Compile the plugin for production
```
npm run build
```
NOTE: this template is NOT configured for building FigJam plugins

## :computer: Running in Figma
In the Figma desktop app, Navigate to the `Plugins` menu via the user dropdown
\
\
Under `In development`, open the menu and select `Import plugin from manifest...`
\
\
Select the `manifest.json` file in the project root folder
\
\
Open any Figma board and load the plugin from the `Plugins > Development` menu

## :scroll: All Available Commands
Build for development (enables auto-compile)
```
npm run dev
```
Build for production (outputs a minified bundle)
```
npm run build
```
Run code formatter
```
npm run format
```
Formatter can be configured by editing .prettierrc — refer to the [Prettier Options page](https://prettier.io/docs/en/options.html) for a list of all available options
