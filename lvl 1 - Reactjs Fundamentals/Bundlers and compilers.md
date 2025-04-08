## Compilers

Compilers are designed to solve the problem of website compatibility in browsers that have different versions (compilers) of Javascript. For example: `babel`.

## Bundlers

TypeScript is a great evolution of JS, but there is a problem: browsers do not know how to interpret ecmaScript modules (imports and exports), so we need a bundler to do this.

Bundlers are module interpreters (ecmaScript imports and exports), which generate a unique code to be interpreted by the browser (which does not know how to use modules). For example: `webpack`, `Vite` e `Snowpack`.

Vite already performs the compilation process automatically (no need for Babel) and is natively compatible with ecma modules.

The [Can I Use ](https://caniuse.com/?search=es%20modules) reveals which browsers are already natively compatible with this ecma module mechanism…

