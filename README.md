[![npm](https://img.shields.io/npm/v/@kronos-integration/interceptor-line-tokens2obj.svg)](https://www.npmjs.com/package/@kronos-integration/interceptor-line-tokens2obj)
[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)
[![minified size](https://badgen.net/bundlephobia/min/@kronos-integration/interceptor-line-tokens2obj)](https://bundlephobia.com/result?p=@kronos-integration/interceptor-line-tokens2obj)
[![downloads](http://img.shields.io/npm/dm/@kronos-integration/interceptor-line-tokens2obj.svg?style=flat-square)](https://npmjs.org/package/@kronos-integration/interceptor-line-tokens2obj)
[![GitHub Issues](https://img.shields.io/github/issues/Kronos-Integration/interceptor-line-tokens2obj.svg?style=flat-square)](https://github.com/Kronos-Integration/interceptor-line-tokens2obj/issues)
[![Build Status](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Factions-badge.atrox.dev%2FKronos-Integration%2Finterceptor-line-tokens2obj%2Fbadge\&style=flat)](https://actions-badge.atrox.dev/Kronos-Integration/interceptor-line-tokens2obj/goto)
[![Styled with prettier](https://img.shields.io/badge/styled_with-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)
[![Known Vulnerabilities](https://snyk.io/test/github/Kronos-Integration/interceptor-line-tokens2obj/badge.svg)](https://snyk.io/test/github/Kronos-Integration/interceptor-line-tokens2obj)
[![Coverage Status](https://coveralls.io/repos/Kronos-Integration/interceptor-line-tokens2obj/badge.svg)](https://coveralls.io/github/Kronos-Integration/interceptor-line-tokens2obj)

# API

<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

### Table of Contents

*   [Transform](#transform)
*   [constructor](#constructor)
    *   [Parameters](#parameters)
*   [\_transform](#\_transform)
    *   [Parameters](#parameters-1)
*   [addError](#adderror)
    *   [Parameters](#parameters-2)
*   [Tokens2ObjectInterceptor](#tokens2objectinterceptor)

## Transform

This module will turn an array of tokens into an object.

## constructor

Creates the line tokenizer and sets the options.
The following options are supported:
{
"header" : \['a', 'b', 'c', undefined, 'e'],
"strict" : false,
"severity" : 'skip_record',
"skip_first_row" : true
}

### Parameters

*   `opts`   (optional, default `{}`)

## \_transform

Reads the stream data and split it into lines.

### Parameters

*   `data`  
*   `enc`  
*   `cb`  

## addError

Adds an error to the stream data

### Parameters

*   `data`  The current stream data
*   `error`  The error to be added.

## Tokens2ObjectInterceptor

**Extends Interceptor**

This interceptor cares about the handling of the messages.
It will add the hops and copies the messages
