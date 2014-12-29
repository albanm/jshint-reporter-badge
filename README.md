# jshint-reporter-badge

[![Build status](https://img.shields.io/travis/albanm/jshint-reporter-badge.svg)](https://travis-ci.org/albanm/jshint-reporter-badge)

*A simple jshint reporter that produces a badge inspired by shields.io*

For example this badge is self served by this project, not by any service provider: [![JSHint status](http://albanm.github.io/jshint-reporter-badge/jshint-badge.svg)](http://albanm.github.io/jshint-reporter-badge/jshint.html)

## Install

    npm install jshint-reporter-badge

## usage

    jshint --reporter node_modules/jshint-reporter-badge/index.js file.js > badge.svg
