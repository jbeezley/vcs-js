vcs.js
======

For documentation see the [interface document](https://docs.google.com/a/kitware.com/document/d/1pY-C4o3JRejKyTja-ScLdx4U9pHFxcWzeptT32KOVgY/edit?usp=sharing).

Useful npm commands:
```bash
npm run build      # build the library to dist/vcs.js
npm run test       # run all tests
npm run test:serve # start test service (runs as files change)
npm run demo       # serve the demo page at http://localhost:8080/demo/
```

While serving tests, you can debug them in the browser at [http://localhost:9876/debug.html](http://localhost:9876/debug.html).
This will also serve the coverage results at [http://localhost:9876/coverage/index.html](http://localhost:9876/coverage/index.html).
