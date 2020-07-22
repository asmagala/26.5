# Random ID-Generator

Package that exports randomID(length) function to generate random ID. It returns a string of small and capital letters and digits.

Created as an exercise for Kodilla bootcamp.

# Prerequisites

Node.js and npm or yarn installed.

# Install

`$ yarn add @asmagala/randomid-generator`

or 

`$ npm i @asmagala/randomid-generator`

# Params:

length - an integer - length of created id string.

# Usage

 - Import (require) module

```
const randomID = require('@asmagala/randomid-generator');
```

 - Use function randomID 
 (for example:) 

```
const length = 12;  // length of created string - a parameter
const signID = randomID(length); 
```