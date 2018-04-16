# NativeScript

## Create an Angular + NativeScript project
```bash
# create an Angular project and change to the app folder
tns create <app-name> --ng
cd <app-name>
```

## Install SASS
Copy the following SASS rules to the application's folder:  
https://github.com/soloproyectos-docs/nativescript/blob/master/.sass-lint.yml

Install SASS:
```bash
tns install sass
```

## Install Linter for TypeScript
Copy the following Linter rules to the application's folder:  
https://github.com/soloproyectos-docs/nativescript/blob/master/tslint.json

Install Linter:
```bash
npm install codelyzer
npm install tslint
```

## Initiate a GIT repository:
Copy the following gitignore file to the applications's folder:  
https://github.com/soloproyectos-docs/nativescript/blob/master/.gitignore

Create the repository and commit:
```bash
git init
git add .
git commit -m 'first commit'
```

## Running and debugging applications

Install an Android emulator (for example [Genymotion](https://www.genymotion.com/)) and execute any of the following commands:
```bash
# run the application in the emulator
tns run <app-name> <android|ios|etc>

# debug the application in the emulator
rns debug <app-name> <android|ios|etc>
```

