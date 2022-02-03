## Problem

The project builds successfully but the built wasm pkg returns an error when run
```
$ node test.js
wasm://wasm/00028e6e:1


RuntimeError: unreachable
    at wasm://wasm/00028e6e:wasm-function[45]:0x6e4c
    at wasm://wasm/00028e6e:wasm-function[62]:0x794b
    at wasm://wasm/00028e6e:wasm-function[93]:0x84d4
(...)
```
## Build:
```wasm-pack build --target nodejs```

## Test / Reproduce Error:
```node app.js```