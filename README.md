html-cleaner
============

A small utility library providing utility methods to 'escape' and 'unescape' HTML entities

## Installation

	npm install html-cleaner --save

## Usage

	var cleaner = require('html-cleaner'),
		escape = cleaner.escape,
		unescape = cleaner.unescape;

	var html = '<h1>Hello world!</h1>',
		escaped = escape(html),
		unescaped = unescape(escaped);

	console.log('html', html, 'escaped', escaped, 'unescaped', unescaped);

## Tests

	npm test


## Release history

	* 0.1.0 Initial release