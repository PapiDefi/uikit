# 🥞 PapiDefi UIkit

[![Version](https://img.shields.io/npm/v/@papidefi/uikit)](https://www.npmjs.com/package/@papidefi/uikit) [![Size](https://img.shields.io/bundlephobia/min/@papidefi/uikit)](https://www.npmjs.com/package/@papidefi/uikit)

PapiDefi UIkit is a set of React components and hooks used to build pages on PapiDefi's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @papidefi/uikit`

## Setup

### Theme

Before using PapiDefi UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@papidefi/uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@papidefi/uikit'
...
<ResetCSS />
```
