# 🐕 SincereDoge UIkit

[![Version](https://img.shields.io/npm/v/@sinceredogeswap/uikit)](https://www.npmjs.com/package/@sinceredogeswap/uikit) [![Size](https://img.shields.io/bundlephobia/min/@sinceredogeswap/uikit)](https://www.npmjs.com/package/@sinceredogeswap/uikit)

SincereDoge UIkit is a set of React components and hooks used to build pages on SincereDoge's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @sinceredogeswap/uikit`


## Setup

### Theme

Before using SincereDoge UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@sinceredogeswap/uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@sinceredogeswap/uikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.
