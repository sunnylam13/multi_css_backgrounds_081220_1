# Prepros Boilerplate v1.0.0

## Documentation

Add your source files to the appropriate `src` subdirectories. Prepos will process and and compile them into `dist`.

- JavaScript files in the `src/js` directory will be compiled to `dist/js`. Files in subdirectories under the `js` folder will be concatenated. For example, files in `js/detects` will compile into `detects.js`.

- Files in the `src/sass` directory will be compiled to `dist/css`.

<!-- - SVG files placed in the `src/svg` directory will be optimized with SVGO and compiled into `dist/svg`. -->

<!-- - Files and folders placed in the `copy` directory will be copied as-is into the `dist` directory. -->

- You have to copy everything in the `src/svg` directory as is into the `dist/svg` directory when you're ready to go live.

- The other option is to copy the initial items in `src/scg` into `dist/svg` then copy it from `dist/svg` to `src/svg` as an archive when you go live...

- You have to copy everything in the `src/copy` directory as is into the `dist` directory when you're ready to go live.

- The other option is to copy the initial items in `src/copy` into `dist` then copy it from `dist` to `src/copy` as an archive when you go live...

- When you copy this boilerplate...  enable File Watcher in Prepros...

- Also delete the current `.git` if it's a new project...