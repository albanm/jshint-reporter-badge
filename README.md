# jshint-reporter-badge

[![Build status](https://img.shields.io/travis/albanm/jshint-reporter-badge.svg)](https://travis-ci.org/albanm/jshint-reporter-badge)

*A simple jshint reporter that produces a badge inspired by shields.io*

## Install

    npm install jshint-reporter-badge

## usage

    jshint --reporter node_modules/jshint-reporter-badge/index.js file.js > badge.svg

You can configure it using environment variables, for example:

    export JSHINT_BADGE_SUBJECT=lint
    export JSHINT_BADGE_OK_COLOR=green
    export JSHINT_BADGE_KO_COLOR=orange
    export JSHINT_BADGE_STYLE=flat