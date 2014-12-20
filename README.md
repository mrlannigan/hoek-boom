hoek-boom
=========

![hoek Logo](https://raw.github.com/hapijs/hoek/master/images/hoek.png)

+

![boom Logo](https://raw.github.com/hapijs/boom/master/images/boom.png)

\+ a few additions

# Introduction

This library extends and exposes [Hoek](https://github.com/hapijs/hoek) and also exposes [Boom](https://github.com/hapijs/boom).

# Additional Features

On top of the already exposed Hoek module API.

### assertBoom( condition, message, errorName )

```js
var a = 1, b = 2;

HoekBoom.assertBoom(a === b, 'a should equal b', 'expectationFailed');  // ABORT: a should equal b, throw boom error
```

### Boom

```js
var Boom = HoekBoom.Boom;

reply(Boom.notFound('stuff wasn\'t found here'));
```