# AngularSchoolC5

Proyecto [Angular CLI](https://github.com/angular/angular-cli) version 9.1.12 LTS
   - **Install** `npm install -g @angular/cli@9.1.12` / Instala una versión espacífica de angular
   - Download NVM [Múltiples versiones de #Nodejs Windows10](https://github.com/coreybutler/nvm-windows/releases)
 => Video: [Link video](https://www.youtube.com/watch?v=iG4u1MK7N3I)
        - `nvm list` / **Ver todas las versiones** de NodeJs instalados
        - `nvm uninstall 8.12.0`  / **Desinstala** versiones anteriores
        - `nvm install 12.13.0` / **Instala** una version específica de NodeJs
        - `nvm use 12.13.0` / **Cambia la version** de node que deseas usar

## Gestores de paquetes de Node
1. NPM
    - `npm install` **Instala las dependencias** del package.json
    - `npm run build` Permite realizar cualquier tarea de construcción/preparación necesaria para el proyecto
2. YARN
    > Como tienes npm instalado, puedes usarlo para instalar yarn
    - Instalar yarn: `npm install -g yarn` 
    > Tienes que instalar la CLI de Angular a nivel global, pero esta vez en Yarn.
    - Instalar la CLI de Angular en Yarn: `yarn global add @angular/cli`
    > Utilizar yarn en vez de npm
    - `yarn install` Utiliza yarn para **instalar las dependencias**

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Build

`ng build` Para **construir las aplicaciones y desplegar** los artefactos de construcción. Se almacenarán en la carpeta `dist/`. Usa `--prod` para una construcción de producción.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

# Markdown

Vea los diferentes elementos de **sintaxis de Markdown**. [markdown.es](https://markdown.es/sintaxis-markdown/)
