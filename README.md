# All Scratch modules together
Joining all Scratch modules packing as a single one. So joins all those:

- [@scratch-css/scratch](https://github.com/scratch-css/scratch) - Main Library
- [@scratch-css/grid](https://github.com/scratch-css/grid) - Grid system
- [@scratch-css/ui](https://github.com/scratch-css/ui) - UIkit
- [@scratch-css/helpers](https://github.com/scratch-css/helpers) - Helpers
- [@scratch-css/animations](https://github.com/scratch-css/animations) - Animations

To know more about Scratch and its modules [read more here](https://github.com/scratch-css/scratch).

### Installing:

    npm install @scratch-css/all --save

### Using in your CSS:    

You need to import it in your CSS file:
  
    @import '@scratch-css/scratch';
    
Or, import from `node_modules` path:

    @import './node_modules/@scratch-css/scratch/index.css';

Try to add this snippet in your CSS just to check if it works:

    body { background-color: var(--success) !important; }
    
Background must be green, [is not it](https://github.com/scratch-css/scratch/issues)?
