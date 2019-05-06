# status-dapp

Simple Dapp

### Installation:

```
npm install
npm run build
```

## Development Mode

### Run application:

```
lein figwheel-repl
```

Figwheel will automatically push cljs changes to the browser.

Wait a bit, then browse to [http://localhost:3449](http://localhost:3449).

## Production Mode

### Build CLJS:

```
lein build-prod
```

Open `resources/public/index.html` in the browser.

### Deploy

```
lein build-prod
cp resources/public/js/compiled/app.js ../status-im.github.io/src/dapp/js/compiled/app.js
```