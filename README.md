# laravel-elixir-phplint

> Support for Laravel Elixir 6+

## Install

> This package is a fork of huntwj/laravel-elixir-phplint. It seems the project is abandond.

```bash
$ npm install laravel-elixir-phplint --save-dev
```

or during development for the latest version:

```bash
$ npm install huntwj/laravel-elixir-phplint --save-dev
```

## Usage

### Example Gulpfile

```javascript
var elixir = require('laravel-elixir');

require('laravel-elixir-phplint');

elixir(function(mix) {
  mix.phplint();
}
```
### Advanced Example

```javascript
var elixir = require('laravel-elixir');

require('laravel-elixir-phplint');

elixir(function(mix) {
  mix.phplint([
    'app/**/*.php',
    'test/**/*.php'
  ]);
}
```

## Credits

The general form and structure as well as some code snippets of this plugin were borrowed
(or viciously stolen?) from the ponko2/laravel-elixir-eslint project on Github.
