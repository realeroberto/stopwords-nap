# Neapolitan stopwords collection

[![Build Status](https://travis-ci.org/robertoreale/stopwords-nap.svg?branch=master)](https://travis-ci.org/robertoreale/stopwords-nap)

The most comprehensive collection of stopwords for the Neapolitan language.

Inspired by Gene Diaz's [comprehensive collection](https://github.com/stopwords-iso).

## Usage

The collection comes in a
[JSON format](https://raw.githubusercontent.com/robertoreale/stopwords-nap/master/stopwords-nap.json) and a
[text format](https://raw.githubusercontent.com/robertoreale/stopwords-nap/master/stopwords-nap.txt).
You are free to use this collection any way you like.
It is only currently published on [npm](https://www.npmjs.com/stopwords-nap) and [bower](https://bower.io).

```sh
$ npm install stopwords-nap
```

```sh
$ bower install stopwords-nap
```

```js
// Node
const stopwords = require('stopwords-nap'); // array of stopwords
```

## Contributing

If you wish to remove or update some of the stopwords, please file an issue first before sending a PR on the repo of the specific language.

If you would like to add a stopword or a new set of stopwords, please add them as a new text file insie the `raw` directory then send a PR.
