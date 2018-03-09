## Introduction

This library converts a given currency into another given currency or currencies.


## Install

Run ```npm install``` in this directory to install all the needed libraries.


## Usage

Run ```node bin/index.js``` in order to see the help. You can use this library that way :  

```node bin/index.js <amount> <currency>``` To convert the given amount from the given currency, by default it will convert it to EUR and GBP.  

```node bin/index.js <command>``` To use one of the following commands :

```--save,  -s```       Save currencies as default currencies
```--help,  -h```       Display help message
```--version,  -v```     Display version number


For example :

```node bin/index.js 1 usd``` To convert 1 USD (by default, to EUR and GBP)

```node bin/index.js 1 usd eur pln aud``` To convert 1 USD to EUR, PLN and AUD

```node bin/index.js --save usd eur pln aud``` To convert 1 USD to EUR, PLN and AUD and save them as default currencies, that way next time you will just have to do ```node bin/index.js 5``` for example to convert 5 USD to EUR, PLN and AUD.

```node bin/index.js --help``` To see the help.
