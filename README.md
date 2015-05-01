svg-transform-parser
====================

Parse SVG transform in Javascript

## Installation

    npm install svg-transform-parser

## Usage

    var parseSvgTransform = require('svg-transform-parser').parse;

    parseSvgTransform("translate(10,20)");
    // {translate: {tx: 10, ty: 20}}

## Compile pegjs

    npm run-script compile

## Tests
  
    npm test