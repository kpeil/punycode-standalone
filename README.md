# punycode-standalone
A standalone IE-friendly mod of the punycode@2.0.0 lib

Punycode uses ES6 syntax and js elements normally requiring polyfills or babel-runtime on IE. Both punycode and babel-runtime use CJS module syntax. Using polyfills or including babel-runtime seems like risk-prone.

This will fetch punycode, transpile it to ES5 and bundle it with required elements from babel-runtime, defining it with the name 'punycode' in requirejs module syntax.
Calling 'npm run full' will  output the bundle into dist/punycode.js

Scripts depend on a unix-style shell.