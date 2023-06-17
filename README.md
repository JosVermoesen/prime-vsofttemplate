# PrimeVsofttemplate

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.1.0.

## Development Tools used for this app on march 2023

- [NodeJS(v18.16.0)](https://nodejs.org/)
- [Angular CLI](https://www.npmjs.com/package/@angular/cli): `npm i -g @angular/cli@16`
- [Visual Studio Code](https://code.visualstudio.com/)

## My favorite extensions

- [Angular Files](https://marketplace.visualstudio.com/items?itemName=alexiv.vscode-angular2-files)
- [Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)
- [Angular 2 TypeScript Snippets](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2)
- [Angular2-switcher](https://marketplace.visualstudio.com/items?itemName=infinity1207.angular2-switcher)
- ASM Code Lens
- [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)
- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
- [Auto Import](https://marketplace.visualstudio.com/items?itemName=steoates.autoimport)
- [Auto-Open Markdown Preview](https://marketplace.visualstudio.com/items?itemName=huntertran.autoopen-markdown-preview)
- [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)
- [Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)
- C# Extensions for Visual Studio Code (powered by OmniSharp) - C/C++ Extensions for Visual Studio Code (powered by Microsoft)
- Ionic
- LaTeX Workshop - LaTeX language support, compiling, viewing, and IntelliSense for Visual Studio Code.
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
- [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)
- [Markdown Shortcuts](https://marketplace.visualstudio.com/items?itemName=mdickin.markdown-shortcuts)
- [Markdown Table Prettify](https://marketplace.visualstudio.com/items?itemName=darkriszty.markdown-table-prettify)
- [Markdown Theme Kit](https://marketplace.visualstudio.com/items?itemName=ms-vscode.Theme-MarkdownKit)
- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
- Path Intellisense - Visual Studio Code plugin that autocompletes filenames
- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- solidity - Solidity language support for Visual Studio Code

## Good practices: use lazy loading modules

- Generate modules ex. a help module: `ng generate module modules/help --route help --module app.module`
- Generate modules ex. a contact module: `ng generate module modules/contact --route contact --module app.module`

## Updating to latest Angular 16

This app is on Angular 16. Before starting an update, always commit first any valid open changes

### update app to latest Angular 16

`ng update @angular/cli@16 @angular/core@16`

### update from older Angular versions to the latest

Follow the instructions in the [Angular Update Guide](https://update.angular.io/) to fix your app.

Please note that then the --force flag is mostly required to be sure that the update command runs even if there are dependency conflicts for thirth party libraries.

#### example upgrade from Angular 16 to Angular 17

`ng update @angular/cli@17 @angular/core@17 --force`

#### npm outdated

In terminal use `npm outdated` to see what packages are requiring updates and what their current and wanted versions are.

This will also show you which packages are deprecated. You can update all packages, or just some of them, by running npm update [package-name].

If you want to update a package to a version newer than what is specified in your package.json, you can do so by running npm update [package-name]@[version-number].

If you want to update all packages to the latest version (regardless of what version is specified in the package.json), you can do so by running
`npm update --latest` .

### Use latest global Angular CLI

`npm i -g @angular/cli`
