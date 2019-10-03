# react-scrolltop

[![license](https://img.shields.io/github/license/nzambello/react-scrolltop.svg)](https://github.com/nzambello/react-scrolltop/blob/master/LICENSE)
[![npm version](https://badge.fury.io/js/%40nzambello%2Freact-scrolltop.svg)](https://www.npmjs.com/package/@nzambello/react-scrolltop)
[![npm](https://img.shields.io/npm/dt/%40nzambello%2Freact-scrolltop.svg)](https://www.npmjs.com/package/@nzambello/react-scrolltop)

React component that adds a 'scroll to top' button fixed on the bottom of the page and shown if not scrolled up.

## Installation

Install the package with either yarn or npm.

With yarn:

```sh
yarn add @nzambello/react-scrolltop
```

With npm:

```sh
npm install --save @nzambello/react-scrolltop
```

## Usage

```js
import React from 'react'
import ReactDOM from 'react-dom'
import ScrollTop from '@nzambello/react-scrolltop'

const App = () => (
  ...
  <ScrollTop />
)

ReactDOM.render(<App />, document.getElementById('root'))
```
