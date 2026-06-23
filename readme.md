<div align='center'>

<h1>TypeBox Script</h1>

<p>Syntax Highlighting for TypeBox Script</p>

<img src="https://github.com/sinclairzx81/typebox-script/raw/main/typebox-script.png" />

<br />
<br />

[![TypeBox Script](https://badgen.net/vs-marketplace/v/sinclairzx81.typebox-script?label=TypeBox+Script+on+Visual+Studio+Marketplace)](https://marketplace.visualstudio.com/items?itemName=sinclairzx81.typebox-script)
</div>

## Overview

Provides syntax highlighting for TypeBox and TypeDriver Script definitions.

Licence MIT

## Matching

The following signatures will match

```typescript
const A = Type.Script(`{ x: number }`)

const B = t.Script(`{ x: number }`)

const C = Script(`{ x: number }`)

const D = compile(`{ x: number }`)

const E = type(`{ x: number }`)

const F = t(`{ x: number }`)

const G = s(`{ x: number }`)
```

## Install

Search for `TypeBox Script` in the VS Code Extensions panel, or install via the command line:

```bash
code --install-extension sinclairzx81.typebox-script
```

## Contribute

TypeBox Script is open to community contribution. Please ensure you submit an issue before submitting a pull request. The TypeBox project prefers open community discussion before accepting new features.





