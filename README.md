# generator-university [![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Dependency Status][daviddm-image]][daviddm-url]
> A generator for creating LaTeX based university documents.

## Installation

First, install [Yeoman](http://yeoman.io) and generator-university using [npm](https://www.npmjs.com/) (we assume you have pre-installed [node.js](https://nodejs.org/)).

```bash
npm install -g yo
npm install -g generator-university
```

Then generate your new project:

```bash
yo university
```

Assuming that a LaTeX suite has been installed and is available on your $PATH, the document can be compiled:
```bash
latexmk -f -pdf
```
This will produce the file ```main.pdf```.

## Getting To Know Yeoman

 * Yeoman has a heart of gold.
 * Yeoman is a person with feelings and opinions, but is very easy to work with.
 * Yeoman can be too opinionated at times but is easily convinced not to be.
 * Feel free to [learn more about Yeoman](http://yeoman.io/).

## License

GPL-3.0 © [Christopher McMorran]()


[npm-image]: https://badge.fury.io/js/generator-university.svg
[npm-url]: https://npmjs.org/package/generator-university
[travis-image]: https://travis-ci.org/chrismcmorran/generator-university.svg?branch=master
[travis-url]: https://travis-ci.org/chrismcmorran/generator-university
[daviddm-image]: https://david-dm.org/chrismcmorran/generator-university.svg?theme=shields.io
[daviddm-url]: https://david-dm.org/chrismcmorran/generator-university
