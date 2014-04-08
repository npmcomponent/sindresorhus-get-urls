*This repository is a mirror of the [component](http://component.io) module [sindresorhus/get-urls](http://github.com/sindresorhus/get-urls). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/sindresorhus-get-urls`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# get-urls [![Build Status](https://travis-ci.org/sindresorhus/get-urls.svg?branch=master)](https://travis-ci.org/sindresorhus/get-urls)

> Get all urls in a string

The urls will be normalized and uniquified.


## Install

Download [manually](https://github.com/sindresorhus/get-urls/releases) or with a package-manager.

```bash
$ npm install --save get-urls
```

```bash
$ bower install --save get-urls
```

```bash
$ component install sindresorhus/get-urls
```


## Usage

```js
var text = 'Lorem ipsum dolor sit amet, sindresorhus.com consectetuer adipiscing http://yeoman.io elit.';

getUrls(text);
//=> ['http://sindresorhus.com', 'http://yeoman.io']
```


## CLI

You can also use it as a CLI app by installing it globally:

```bash
$ npm install --global get-urls
```

#### Usage

```bash
$ get-urls -h

get-urls <input-file>
or
cat <input-file> | get-urls
```


## License

[MIT](http://opensource.org/licenses/MIT) © [Sindre Sorhus](http://sindresorhus.com)
