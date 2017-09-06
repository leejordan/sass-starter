# Sass-starter

barebones sass compilation and styleguide generation

## Technical info

### Requirements

- [node.js](https://nodejs.org/en/download/)

### Setup

```
git clone https://github.com/leejordan/sass-starter.git
cd sass-starter
npm install
```

### Usage

#### Local server

```
npm run start // starts a local server for styleguide on http://localhost:8080
```

#### Build css and styleguide

```
npm run build:min // builds minified css in css folder
npm run build:max // builds uncompressed css in css folder
npm run build:docs // builds the static styleguide in styleguide folder
npm run build // all of the above
npm run watch // all of the above every time a file changes in scss folder
```
