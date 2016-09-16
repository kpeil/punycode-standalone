# punycode-standalone
A standalone IE-friendly mod of the punycode@2.0.0 lib

Punycode uses ES6 syntax and js elements normally requiring polyfills or babel-runtime. Both use CJS module syntax.

This will fetch punycode, transpile it to ES5 and bundle it with required polyfills, using requirejs module syntax.
Calling 'npm run full' will eventually output the bundle into dist/standalone/punycode.js

Scripts depend on a unix-style shell.