## BMI Calculator

[![Build Status](https://travis-ci.com/GermaVinsmoke/bmi-calculator.svg?branch=master)](https://travis-ci.com/GermaVinsmoke/bmi-calculator)
[![Coverage Status](https://coveralls.io/repos/github/GermaVinsmoke/bmi-calculator/badge.svg?branch=master)](https://coveralls.io/github/GermaVinsmoke/bmi-calculator?branch=master)
[![codecov](https://codecov.io/gh/GermaVinsmoke/bmi-calculator/branch/master/graph/badge.svg)](https://codecov.io/gh/GermaVinsmoke/bmi-calculator)

React Hooks app to calculate the BMI of a person. It can store the data for 7 days with the help of LocalStorage.

![](images/1.jpg)

Created with _create-react-app_. See the [full create-react-app guide](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md).

## Install

`npm install`

## Usage

`npm start`

##

`npm test a`

## Enhancement

1. Removing the dependency of Materialize-CSS module

~~2. Chart going crazy on hovering over the old points~~

## Run with docker

1. Clone and cd into repository
2. Build docker image: `docker build -t bmi-calculator .`
3. Run container with built image: `docker run -ti -p 127.0.0.1:8080:80 bmi-calculator`
4. Visit `http://127.0.0.1:8080/` on you browser.
