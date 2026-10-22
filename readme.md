<div align="center">

<h1>TypeBox Script</h1>

<p>Syntax Highlighting for TypeBox Types</p>

<img src="https://github.com/sinclairzx81/typebox-script/raw/main/typebox-script.png" alt="TypeBox Script" />

<br />
<br />

[![TypeBox Script](https://badgen.net/vs-marketplace/v/sinclairzx81.typebox-script?label=TypeBox+Script+on+Visual+Studio+Marketplace)](https://marketplace.visualstudio.com/items?itemName=sinclairzx81.typebox-script)
</div>

## Overview

Provides syntax highlighting for TypeBox Script definitions.

License: MIT

## Module

This extension provides syntax highlighting for TypeBox type modules that use the `.box`, `.tb`, or `.tbx` extension. These modules must contain only TypeScript definitions.

The `.box`, `.tb`, and `.tbx` extensions use separate TypeBox Script language modes to provide distinct cube icons while sharing the same syntax highlighting.

Use `Ctrl+/` (or `Cmd+/` on macOS) to toggle `//` comments on the current line or selected lines. TypeBox modules also support TypeScript-style block comments, bracket matching and auto-pairing, word selection, region folding, and indentation.

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