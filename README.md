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
npm run build:min // builds minified css in styleguide/css folder
npm run build:max // builds uncompressed css in styleguide/css folder
npm run build:styleguide // builds the static styleguide in styleguide folder
npm run build // all of the above
npm run watch // all of the above every time a file changes in scss folder
```

#### Updating styleguide theme

You can build a new css file for the styleguide theme by changing `styleguide-template/scss/styleguide.scss` and using these commands.

```
npm run build:styleguide-css // builds css file for the styleguide builder to use
npm run watch:styleguide-css // runs the build above every time a file changes in styleguide-template/scss
```

