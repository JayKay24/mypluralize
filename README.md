[![Build Status](https://travis-ci.org/JayKay24/mypluralize.svg?branch=master)](https://travis-ci.org/JayKay24/mypluralize)
[![Coverage Status](https://coveralls.io/repos/github/JayKay24/mypluralize/badge.svg?branch=master)](https://coveralls.io/github/JayKay24/mypluralize?branch=master)
# sample-mypluralize
Create a simple Typescript package. A node.js module that returns the plural form
of any noun.

## Installation
```
npm install sample-mypluralize --save
yarn add sample-mypluralize
bower install sample-mypluralize --save
```

## Usage

### Javascript

```
var pluralise = require('sample-mypluralize');
var boys = pluralise.getPlural('Boy');
```
```
Output should be 'Boys'
```

## Typescript
```
import { getPlural } from 'sample-mypluralize'
console.log(getPlural('Goose'))
```
```
Output should be 'Geese'
```

### AMD
```
define(function(require, exports, module)) {
  var pluralise = require('sample-mypluralize')
}
```

## Test
```
npm run test
```
