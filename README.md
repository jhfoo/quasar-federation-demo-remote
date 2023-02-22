# quasar-federation-demo
Demonstrates micro front-end implementation with vue 3 and vite 

## Create host
1. Create host app with `npm create vue@3`.
2. Install federation plugin: `npm i -D @originjs/vite-plugin-federation`
3. Install dependencies: `npm i`
4. Fix a transpile bug/error by adding the following into vite.config.js:

Ref: https://github.com/vitejs/vite/issues/6985
```
build: {
  target: 'esnext'
}
```

## Remote remote
1. Create remote module with `npm create vue#3`.
2. Install federation plugin: `npm i -D @originjs/vite-plugin-federation`
3. Install dependencies: `npm i`
4. Fix a transpile bug/error by adding the following into vite.config.js:

Ref: https://github.com/vitejs/vite/issues/6985
```
build: {
  target: 'esnext'
}
```
