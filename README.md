# laravel-elixir-phplint

> Support for Laravel Elixir 6+

## Install

```bash
$ npm install laravel-elixir-6-phplint --save-dev
```

or during development for the latest version:

```bash
$ npm install huntwj/laravel-elixir-6-phplint --save-dev
```

## Usage

### Example Gulpfile

```javascript
require('laravel-elixir-6-phplint');

elixir(function(mix) {
  mix.phplint();
}
```
### Advanced Example

```javascript
require('laravel-elixir-6-phplint');

elixir(function(mix) {
  mix.phplint([
    'app/**/*.php',
    'test/**/*.php'
  ]);
}
```

## Credits

> This package is a fork of huntwj/laravel-elixir-phplint. It seems the project is abandond.

The general form and structure as well as some code snippets of this plugin were borrowed
(or viciously stolen?) from the ponko2/laravel-elixir-eslint project on Github.
