[![Build Status](https://travis-ci.org/RomanVr/project-lvl3-s394.svg?branch=master)](https://travis-ci.org/RomanVr/project-lvl3-s394)
[![Maintainability](https://api.codeclimate.com/v1/badges/d17dde6f8843fb00d9d4/maintainability)](https://codeclimate.com/github/RomanVr/project-lvl3-s394/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/d17dde6f8843fb00d9d4/test_coverage)](https://codeclimate.com/github/RomanVr/project-lvl3-s394/test_coverage)
# project-lvl3-s394
---
This utility allows you to download pages from the network to the directory (output).

## Install
---
Type a command in the terminal:
`git clone https://github.com/RomanVr/project-lvl3-s406.git`

go to the folder you created: `cd project-lvl3-s394`

then sequentially: `make install` `make build` `sudo npm link`

you can run the utility

## Usage
---
page-loader [options] `<address>`

Options:
    * -V, --version        output the version number
    * -o, --output [dir]  Directory destination (default: "")
    * -h, --help           output usage information

to usage with debug logging: DEBUG=pageLoader page-loader [options] `address`

[Sample usage](https://asciinema.org/a/QgTkLHI7TYTWRBF33mh1cqCuq)