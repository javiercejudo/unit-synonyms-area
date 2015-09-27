# unit-synonyms-area

[![Build Status](https://travis-ci.org/javiercejudo/unit-synonyms-area.svg)](https://travis-ci.org/javiercejudo/unit-synonyms-area)
[![Coverage Status](https://coveralls.io/repos/javiercejudo/unit-synonyms-area/badge.svg?branch=master)](https://coveralls.io/r/javiercejudo/unit-synonyms-area?branch=master)
[![Code Climate](https://codeclimate.com/github/javiercejudo/unit-synonyms-area/badges/gpa.svg)](https://codeclimate.com/github/javiercejudo/unit-synonyms-area)

Mass units synonyms

## Install

    npm i unit-synonyms-area

## Units

- [Square metre](https://en.wikipedia.org/wiki/Square_metre)
- [Hectare](https://en.wikipedia.org/wiki/Hectare)
- [Square mile](https://en.wikipedia.org/wiki/Square_mile)
- [Acre](https://en.wikipedia.org/wiki/Acre)
- [Square yard](https://en.wikipedia.org/wiki/Square_yard)
- [Square foot](https://en.wikipedia.org/wiki/Square_foot)
- [Square inch](https://en.wikipedia.org/wiki/Square_inch)

## Usage

```js
var synonyms = require('unit-synonyms-area').synonyms;

synonyms['km²']; // => squareKilometre
synonyms['square feet']; // => squareFoot
```

## Related projects

- [linear-presets](https://github.com/javiercejudo/linear-presets): linear presets for common units.
- [linear-converter](https://github.com/javiercejudo/linear-converter): flexible linear converter.
