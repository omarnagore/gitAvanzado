# gitAvanzado
Curso Git Avanzado

# README BONITO
Readme presentado con formato

## Prerequisites
Tener Node
```bash
$ node -v
```
Si tienes node dirá la versión de NODE si no mostrará lo siguiente:
```bash
$ zsh: command not found: node
```
That means that the command you are trying to run is not installed. There are several ways to install Node.js and NPM:
- Using the macOS installer available from the [Node.js](https://nodejs.org/) website
- Using [homebrew](https://brew.sh/)

## Installation
```bash
$ git clone https://github.com/Servicios-Liverpool-Infraestructura/ICD_Automation_Cypress.git
$ cd ICD_Automation_Cypress/ 
$ npm i
```

## CLI run parameters examples
#### Mobile
```bash
$ npm run cypress:mobile ENV='prod',SITE='www',STORE='liverpool',TAGS='(@bs and @liv) and not (@ignore or @desktop)'
```
#### Desktop
```bash
$ npm run cypress:desktop ENV='prod',SITE='www',STORE='liverpool',TAGS='(@bs and @liv) and not (@ignore)'
```

