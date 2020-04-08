# Frontend boilerplate

A simple HTML5 frontend boilerplate to kick off your responsive websites. Written in SCSS and based on the [BEM](http://getbem.com/) naming convention.

This boilerplate runs on [Parceljs 1.x](https://parceljs.org/) as module bundler and yarn scripts as task runner. Feel free to fork it ;)

- [Demo](https://azuri-frontend-boilerplate.netlify.com)
- [Github repository](https://github.com/AzuriDigital/frontend-boilerplate/)

## Features
- Parceljs [website](https://parceljs.org/) and the benefits of it
- HTML5 template page demo
- Optimised font setup with [Google Fonts](https://fonts.google.com/)
- `Normalize.css` for CSS reset stylesheet
- [Sass](http://sass-lang.com/), mixins and functions (dedicated sass mixin for media queries based on [Sass mq](https://github.com/sass-mq/sass-mq/))
- CSS helper classes
- Basic UI components including:
 - Typography
 - Buttons
 - Blockquote
 - A responsive grid using CSS grid and not flexbox
 - Forms elements
 - Tables
 - Figure
- [Babel](https://babeljs.io/) with [preset-env](https://github.com/babel/babel/tree/master/packages/babel-preset-env) 
- [PostCSS](https://github.com/postcss/postcss): see package.json (unfortunately [Parceljs](https://parceljs.org/) doesn't support well .postcssrc file...)
- [Stylelint](https://stylelint.io/) linter 

### Yarn scripts

- `yarn dev`: start the project on [localhost:8000](http://localhost:8000)
- `yarn build`: build the project in the dist folder
- `yarn prebuild`: remove the dist folder
- `yarn stylelint`: lint all the scss files

### Code formatter

- [Prettier](https://github.com/prettier/prettier)

## Browser support
As it's a personal project I don't want to waste time working on Internet Explorer. However with few polyfills and a flexbox based grid system this project could run on IE...

- Chrome (latest 2)
- Edge (latest 2)
- Firefox (latest 2)
- ~~Internet Explorer 11~~
- Opera (latest 2)
- Safari (latest 2)



## Setup

### Requirements

Use brew or install nodejs from [here](http://nodejs.org/download/) 

```bash
brew install node
```

Node `">=12.6.1"`

Npm `">=6.5.0"`


### Clone the repository

_OSX & Linux_:

```bash
git clone --depth 1 https://github.com/AzuriDigital/frontend-boilerplate.git && cd frontend-boilerplate && rm -rf .git && git init
```

_Windows_:

```bash
git clone --depth 1 https://github.com/AzuriDigital/frontend-boilerplate.git && cd frontend-boilerplate && rd /s /q .git && git init
```

### Install dependencies

```bash
yarn install or npm install
```


## Develop

With yarn:

```bash
yarn dev
```


or with npm:

```bash
npm run dev
```

## Production

```bash
yarn build
```

or with npm:

```bash
npm run build
```

## Licence

MIT
