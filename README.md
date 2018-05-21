# Wolox Equalizer
[![circle-ci](https://img.shields.io/circleci/project/github/Wolox/wolox-equalizer.svg)](https://circleci.com/gh/Wolox/wolox-equalizer)
[![npm](https://img.shields.io/npm/v/wolox-equalizer.svg)](https://www.npmjs.com/package/wolox-equalizer)

[![FEArmy](./assets/FEA_icon.png)](https://github.com/orgs/Wolox/teams/front-end-army/members)
## Features

- Reset the default styles of the browser.
- Contains Wolox standards for normalizing front-end projects.

## Installation

#### npm
```bash
npm i wolox-equalizer
```

#### yarn
```bash
yarn add wolox-equalizer
```

## Usage

Include the equalizer.scss before **any** file of your CSS/SCSS. You can do it by simply using the import statement on top of your root `scss` file:

```scss
@import '~wolox-equalizer/equalizer';
```

Or you can also do the following trick to simply import it with it's name:

```scss
@import 'equalizer';
```

```js
// webpack.config.js
{
  loader: 'sass-loader',
  options: {
    includePaths: ['node_modules/wolox-equalizer']
  }
}
```

## Base Styles

All the text have the base style:
```css
color: #717171;
font-family: sans-serif;
font-size: 14px;
line-height: 14px;
```
And input placeholders:
```css
color: #999
```

## About

This project is maintained by [Francisco Iglesias](https://github.com/frankiglesias) & [Braian Dickson](https://github.com/braiandickson) and it was written by [Wolox](http://www.wolox.com.ar).

![Wolox](https://raw.githubusercontent.com/Wolox/press-kit/master/logos/logo_banner.png)
