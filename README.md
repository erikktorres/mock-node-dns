# mock-net

Dummy replacement of Node's [dns](http://nodejs.org/api/dns.html) module.

Needed so [Joi](https://github.com/hapijs/joi) compiles for the browser with [Webpack](http://webpack.github.io/).

**WARNING**: This just allows the build to work when it sees `require('dns')`. If you try to actually use the module, your program will throw an error.
