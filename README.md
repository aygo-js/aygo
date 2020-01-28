# Aygo

[![Github action](https://github.com/aygo-js/aygo/workflows/Lint,%20Test%20and%20Build/badge.svg)](https://github.com/aygo-js/aygo/actions?query=workflow%3A%22Lint%2C+Test+and+Build%22)
[![CodeFactor](https://www.codefactor.io/repository/github/aygo-js/aygo/badge)](https://www.codefactor.io/repository/github/aygo-js/aygo)
[![Known Vulnerabilities](https://snyk.io/test/github/aygo-js/aygo/badge.svg?targetFile=package.json)](https://snyk.io/test/github/aygo-js/aygo?targetFile=package.json)
[![Maintainability](https://api.codeclimate.com/v1/badges/146ecacdbb5301100b6f/maintainability)](https://codeclimate.com/github/aygo-js/aygo/maintainability)
[![Reviewed by Hound](https://img.shields.io/badge/Reviewed_by-Hound-8E64B0.svg)](https://houndci.com)
![npm](https://img.shields.io/npm/v/aygo)
![npm type definitions](https://img.shields.io/npm/types/aygo)
![Libraries.io dependency status for latest release](https://img.shields.io/librariesio/release/npm/aygo)
![NPM](https://img.shields.io/npm/l/aygo)
![npm](https://img.shields.io/npm/dt/aygo)

Aygo is a simple utility logger for typescript and javascript.

## How to use Aygo

To use aygo just install it via : 

`npm install aygo`

Then you can import it like the following :

```
import { Aygo } from 'aygo';

Aygo.log("LOG : This", "is", { "key": "a test" }, 134);
``` 

OR

```
const aygo = require("aygo");
const Aygo = aygo.Aygo;

Aygo.log("LOG : This", "is", { "key": "a test" }, 134);
 ```

## Methods

For now Aygo supports the basic logging methods (check the examples for more) :

* debug
* log
* info
* warn
* error
