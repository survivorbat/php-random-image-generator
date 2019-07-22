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
2. Run `make run cmd="img:create:random"` to create an image

It might be easier to use the command line of the php container to execute,
in order to get this working use `make shell`, this will bring you to the
shell of a running php environment and allows you to use commands in the form
of: `bin/console list`.

## Plans for the future

- ~~Add image dimensions to CLI~~
- ~~Add more image output types~~
- ~~Perhaps add symfony/console for easier command line management~~
- ~~Create a docker image of the application itself~~
- Add extra parameters to allow user to influence the end result of the image (make a more red, green or blue image result)
- Add xdebug for generating coverage reports
- Add more tests
- Add jpeg and webp output types
- Add more generators
- Add more output formatting
~ Make sure php-cs-fixer works with 7.4

## Known quirks

- Php-cs-fixer is not supported for 7.4 yet
