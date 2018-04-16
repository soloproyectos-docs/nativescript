# NativeScript

## Create a Angular + NativeScript application
```bash
# create an Angular project and change to the app folder
tns create <app-name> --ng
cd <app-name>
```

## Running and debugging applications

Install an Android emulator (for example, [Genymotion](https://www.genymotion.com/)) and execute any of the following commands:
```bash
# run an application in the emulator
tns run <app-name> <android|ios|etc>

# debug an application in the emulator
rns debug <app-name> <android|ios|etc>
```

## Git integration
Add a `.gitignore` file to the Application's root folder and initialize the repository:  
https://github.com/NativeScript/sample-Groceries/blob/master/.gitignore

```bash
git init
git add .
git commit -m 'first commit'
```
## Linter integration

Install [Codelyzer](https://github.com/mgechev/codelyzer)
```bash
npm install codelyzer
typings install
```

and create a `tslint.json` file in the root folder:  
https://github.com/soloproyectos-docs/nativescript/blob/master/tslint.json
