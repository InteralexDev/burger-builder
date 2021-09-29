# Burger Builder (English)

## Table of content
  * [Presentation](#chapter-1)
  * [Installation](#chapter-2)

## Presentation <a name="chapter-1"></a>

### Project description
Burger Builder is a website I created as part of a formation in the HDM network company to learn how the REACT library works.

### License
The REACT library is open-sourced software licensed under the MIT license and created by Facebook since 2013.

## Installation <a name="chapter-2"></a>

### Create a empty project
```bash
npx create-react-app my-app --scripts-version 1.1.5
```

### Add custom css options

#### Make config files visible
```bash
npm run eject
```

#### Modify webpack.config.js
Find "css-loader" with ctrl-f and modify the content like below :
```js
loader: require.resolve('css-loader'),
    options: {
        cssOptions,
        modules: true,
        localIdentName: '[name]__[local]__[hash:base64:5]',
    }
```

#### Install props-types
```bash
npm install --save prop-types
```

### Launching the website
```bash
cd my-app
npm start
```

<p align="center">Copyright © 2021 InteralexDev | all rights reserved</p>