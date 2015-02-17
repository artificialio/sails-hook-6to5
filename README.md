# sails-hook-traceur
[![npm version](https://badge.fury.io/js/sails-hook-babel.svg)](https://npmjs.org/package/sails-hook-traceur) [![Dependency Status](https://img.shields.io/david/artificialio/sails-hook-babel.svg?style=flat)](https://david-dm.org/artificialio/sails-hook-traceur)

*Needs at least Sails version 0.11-rc to work*

[Sails JS](http://sailsjs.org) hook to activate ES6/7 Javascript code for your whole sails app, via [https://babeljs.io/](https://babeljs.io/).

### Installation

`npm install sails-hook-6to5`

### Usage

Just lift your app as normal, and enjoy the future of Javascript today. To see what is possible, see: https://babeljs.io/docs/learn-es6/

### Configuration

By default, configuration lives in `sails.config.babel`.  The configuration key (`babel`) can be changed by setting `sails.config.hooks['sails-hook-babel'].configKey`.

Parameter      | Type                | Details
-------------- | ------------------- |:---------------------------------
compile        | ((boolean)) | Whether or not sails should compile/allow ES6/7 code.  Defaults to `true`.

That&rsquo;s it!