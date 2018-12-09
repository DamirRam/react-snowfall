![Snowfall Demo](./assets/snowfall-demo.gif)

# Snowfall

[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg)](https://conventionalcommits.org)

A react component that creates a snowfall effect

- [Live Example](https://cahilfoley.github.io/snowfall/)
- [Demo Playground](https://codesandbox.io/s/github/cahilfoley/snowfall/tree/demo)

## Installation

With npm

```
npm i @cahil/snowfall
```

Or with yarn

```
yarn add @cahil/snowfall
```

## Usage

Basic usage requires no properties and will take match the size of the parent element.

```jsx
import React from 'react'
import ReactDOM from 'react-dom'
import Snowfall from '@cahil/snowfall'

ReactDOM.render(
  <div style={{ height: 400, width: 400, background: '#282c34' }}>
    <Snowfall />
  </div>,
  document.querySelector('#app')
)
```

## Configuration

An optional `color`, `style`, and `snowflakeCount` property can be passed in to the component.

```jsx
<Snowfall
  // Changes the snowflake color
  color="red"
  // Applied to the canvas element
  style={{ background: '#fff' }}
  // Controls the number of snowflakes that are created (default 150)
  snowflakeCount={200}
/>
```
