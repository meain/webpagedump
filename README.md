# Webpagedump [![npm version](https://badge.fury.io/js/webpagedump.svg)](https://badge.fury.io/js/webpagedump)

Command like thingy to take dump html of a js rendered page


## Installation

```
npm install -g webpagedump
```

or even use with `npx` directly without installing

```
npx webpagedump -u https://meain.io -O meain.html
```

## Usage

```
Usage: webpagedump [options]

Options:
  -V, --version         output the version number
  -u, --url [value]     URL to capture
  -O, --output [value]  output file
  -h, --help            output usage information
```

#### Example

```
webpagedump -u https://github.com/meain/webpagedump -O webpagedump.html
```
