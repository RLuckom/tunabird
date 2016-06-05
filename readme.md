Dependencies
=======

This project assumes use of [nvm](https://github.com/creationix/nvm) to manage
node versions.

```
nvm install v6
npm install -g webpack
npm install -g webpack-dev-server
npm install
```

Setup
=====

For as long as humanly possible I will avoid using a build system like `gulp`,
`grunt`, `broccoli` or whatever in this project. Instead I will rely on
individual tools like `webpack` for building and dev server-ing, 
an as-yet-undecided test tool for testing, and use npm scripts to glue it
all together. JS build systems are the regexes of js project management; they're
powerful but they multiply your problems.

The following are the commands implemented so far:

* `npm run compile` - packages the app in the `dist` directory
* `npm run serve` - Serves the app on `http://localhost:8080` and rebuilds on changes

TODO
=====

Choose test tool.

License
=======

MIT
