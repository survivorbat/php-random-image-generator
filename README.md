# PHP Random image generator

![Example image](docs/example.png "Example image")

This project came to be after a random thought popped into my head about what would happen
if you were to generate a random picture from code with random colors. This is a severely
over-engineered 7-line script that I made out of boredom and my desire to try out php
7.4 and some image creation from code.

## Prerequisites

In order to run this application in an isolated environment and to make installing it
easier, all you need is Docker. It's also advisable to have Make installed to
make use of the makefile.

## Getting started

Setting up the application is as easy as:
1. Run `make install` to install dependencies
2. Run `make run` to run the application

## Plans for the future

- Add extra parameters to allow user to influence the end result of the image (make a more red, green or blue image result)
- Add xdebug for generating coverage reports
- Add image dimensions to CLI
- Add more image output types
- Create a docker image of the application itself (perhaps)
- Perhaps add symfony/console for easier command line management

## Known quirks

- None yet!