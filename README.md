# lazy-load-es2015-webpack2
Challenge for the talk at http://tiagorg.com/talk-lazy-loading-es2015-modules

Lazy-loading ES2015 modules in the browser with Webpack 2, Babel and System.js

# Usage

- Needs Node 4+.

```
npm install
npm run build
./node_modules/http-server/bin/http-server
open http://127.0.0.1:8080/
```

# Instructions
- Fork from [github.com/tiagorg/lazy-load-es2015-webpack2-challenge](https://github.com/tiagorg/lazy-load-es2015-webpack2-challenge)
- Take a moment to understand this implementation.
- Completely lazy-load *`MerryXmas`* and its dependencies upon click of the "Merry Xmas" button.
- Completely lazy-load *`Alert`* after 5s the page has been loaded.
- Verify your lazy-loadable bundles have been generated and are loading properly.
- Use the [dynamic import() operator](http://www.2ality.com/2017/01/import-operator.html).