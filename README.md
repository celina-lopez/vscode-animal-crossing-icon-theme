# VSCode Animal Crossing Icon Theme For Ruby on Rails

A Animal Crossing themed product icon pack!
Currently for common front-end web development file types

![Screen Shot 2022-05-04 at 1 11 50 AM](https://user-images.githubusercontent.com/57647158/166646597-1e9fa28e-8e56-4bd7-b649-8e6168c1e2ce.png)


### Download at https://marketplace.visualstudio.com/items?itemName=celina-lopez.vscode-animal-crossing-icon-theme
![Screen Shot 2022-05-04 at 1 26 38 AM](https://user-images.githubusercontent.com/57647158/166647006-553bd1d2-a2f4-43b2-acc7-602da4fea047.png)


## Development

This extension uses image files directly from the `icons` folder in `icons.json`.

Open this repo in VSCode and hit F5 to test it out.

You will need to run to develop:
```yarn install```
```yarn install -g vsce```

### To publish a new version to the VS Code Extension Marketplace
Update the version number in package.json and run:
```vsce publish```

### To package for sharing with others
Run this command to generate a VSIX file:
 ```vsce package```
To load this VSIX extension into your VS Code IDE, replacing the file name with the generated one:
```code --install-extension vscode-animal-crossing-icon-theme-0.0.7.vsix```
