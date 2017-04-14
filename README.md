# All Scratch modules together

[![Gitter](https://img.shields.io/gitter/room/nwjs/nw.js.svg)](https://gitter.im/scratch-css/all)
[![npm (scoped)](https://img.shields.io/npm/v/@nikoloza/scratch-all.svg)](https://www.npmjs.com/package/@nikoloza/scratch-all)

Joining all Scratch modules and packing as a single one. It includes all of those:

- [@scratch-css/reset](https://github.com/scratch-css/reset) - Scratch reset
- [@scratch-css/scratch](https://github.com/scratch-css/scratch) - Main Library
- [@scratch-css/grid](https://github.com/scratch-css/grid) - Grid system
- [@scratch-css/ui](https://github.com/scratch-css/ui) - UIkit
- [@scratch-css/helpers](https://github.com/scratch-css/helpers) - Helpers
- [@scratch-css/animations](https://github.com/scratch-css/animations) - Animations

To know more about Scratch and its modules you can [read here](https://github.com/scratch-css/scratch).

### Setup:

    npm install @scratch-css/all --save

You need to import it in your CSS file:

    @import '@scratch-css/scratch';

Or, import from `node_modules` path:

    @import '@scratch-css/scratch/index.css';

### Try:

Try to add this snippet in your CSS just to check if it works:

    body { background-color: var(--success) !important; }

Background must be green, [is not it](https://github.com/scratch-css/scratch/issues)?
