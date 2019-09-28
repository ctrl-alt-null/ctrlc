# CTRLCV

>Copies a **simple** JS object using `JSON.stringify` and `JSON.parse`.

## Install
`npm i -S ctrlcv` or `yarn add ctrlcv`

## Usage
```javascript
import copy from "ctrlcv"

const a = { prop1: "wibble", prop2: "wobble" }
const b = copy(a)

b.prop1 = "wubble"

alert(a.prop1 !== v.prop1) //true
```
