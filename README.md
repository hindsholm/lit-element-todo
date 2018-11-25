# lit-element-todo

An adaptation of the simple LitElement ToDo app created as a comparison piece for the article
[LitElement To Do App](https://medium.com/@westbrook/litelement-to-do-app-1e08a31707a4).

This version does not have any npm dependencies and does not require any build steps.
Instead, the lit-element and lit-html dependencies are directly imported in the source code using
ES6 modules and [jspm.io - Native ES Modules CDN](https://jspm.io/).

Since ES6 modules are [supported in all major browsers](https://caniuse.com/#feat=es6-module)
this is now a much simpler way of developing JavaScript applications.
