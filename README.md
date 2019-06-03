# snips-engine-node-ts
[![Build Status](https://travis-ci.com/gjdass/snips-engine-node-ts.svg?branch=master)](https://travis-ci.com/gjdass/snips-engine-node-ts)

## The goal

[Snips](https://snips.ai) is a voice assistant engine made by a French startup.

To work, it needs 2 main things (let's keep that simple) : an intents engine (Snips itself provides that), and an actions engine (this).

_Example_ : wake snips > mic activated > speak > translation into text > **taking action** > translate response into speech > feedback to user

## Before anything

[NodeJS and npm](https://nodejs.org/en/) are required.

```bash
$ npm install -g typescript # install Typescript globally
```

## Run the engine

```bash
$ npm install # well ... install everything
$ npm run build # one time build
$ npm run watch # TSC will wait for changes and recompile each time
$ npm start # it uses nodemon to keep running the app over changes
```

## Cool stuff inside

This list is not static. It will move over time if some new lib/new need appears.

* typescript - Because ... Because.
* lodash - To make everything simpler regarding data sort/manipulation.
* config - To handle the annoying job of dedicate a behavior of the app in certain cases etc.
* cross-env - To avoid having trouble with ENV variables on different OS.
* log4js - To log anything we want, in a console or in an ELK stack or whatever.

## Contributions

PR are very welcome. This is a personal project its development is not linear in time.