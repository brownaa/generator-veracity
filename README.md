# Generator for creating Veracity Apps [![npm version](https://badge.fury.io/js/%40veracity%2Fgenerator-veracity.svg)](https://badge.fury.io/js/%40veracity%2Fgenerator-veracity) [![Dependency Status][daviddm-image]][daviddm-url]



## Installation

First, install [Yeoman](http://yeoman.io) and generator-veracity using [npm](https://www.npmjs.com/) (we assume you have pre-installed [node.js](https://nodejs.org/)).

```bash
npm install -g yo
npm install -g @veracity/generator-veracity
```

Then do the following to generate your projects:

NodeJs demo webapp
```bash
yo @veracity/veracity:node-webapp-demo
```
Run the Nodejs demo webapp
```bash
node start.js
```
Then go to https://localhost:3000 (ignore certificate error if you do not import the cerficate)

Dotnet demo webapp
```bash
yo @veracity/veracity:netcore-webapp
```

## Update

To update your Veracity application generator to the latest release, run the following:

```bash
yo 
```

Select update, and pick the generator to update. Then we fix the rest.


## License

Apache-2.0 © [DNV GL](https://developer.veracity.com)


[npm-image]: https://badge.fury.io/js/generator-veracity.svg
[npm-url]: https://npmjs.org/package/generator-veracity
[travis-image]: https://travis-ci.org/Veracity/generator-veracity.svg?branch=master
[travis-url]: https://travis-ci.org/Veracity/generator-veracity
[daviddm-image]: https://david-dm.org/Veracity/generator-veracity.svg?theme=shields.io
[daviddm-url]: https://david-dm.org/Veracity/generator-veracity
