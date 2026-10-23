<div align="center">

<h1>TypeBox Script</h1>

<p>Syntax Highlighting for TypeBox Types</p>

<img src="https://github.com/sinclairzx81/typebox-script/raw/main/typebox-script.png" alt="TypeBox Script" />

<br />
<br />

[![TypeBox Script](https://badgen.net/vs-marketplace/v/sinclairzx81.typebox-script?label=TypeBox+Script+on+Visual+Studio+Marketplace)](https://marketplace.visualstudio.com/items?itemName=sinclairzx81.typebox-script)
</div>

## Overview

Syntax highlighting for TypeBox Script definitions.

License: MIT

## Module

TypeBox modules use the `.box` or `.type` file extension. These modules must contain TypeScript definitions only. Refer to the [Script](https://sinclairzx81.github.io/typebox/#/docs/script/1_script) documentation for the supported syntax.

## String

Syntax highlighting will match in strings for the following function signatures.

```typescript
const A = Type.Script(`{ x: number }`)

const B = t.Script(`{ x: number }`)

const C = Script(`{ x: number }`)

const D = compile(`{ x: number }`)

const E = type(`{ x: number }`)

const F = t(`{ x: number }`)

const G = s(`{ x: number }`)

const H = x(`{ x: number }`)

const I = y(`{ x: number }`)

const J = z(`{ x: number }`)
```

## Install

Search for `TypeBox Script` in the VS Code Extensions panel, or install via the command line:

```bash
code --install-extension sinclairzx81.typebox-script
```

## Contribute

TypeBox Script is open to community contributions. Please open an issue before submitting a pull request. The TypeBox project prefers open community discussion before accepting new features.