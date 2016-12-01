# ts

`ts` is the command line client for Timberslide. This client is underdevelopment
and may change at any time.

[![GoDoc Reference](https://godoc.org/github.com/timberslide/ts?status.svg)](http://godoc.org/github.com/timberslide/ts)

## Build

[Download a binary](https://github.com/timberslide/ts/releases) or install from command line `go install` (Requires golang to be installed). Tested under golang 1.7.

## Configuration

~/.timberslide/config

```
host = "gw.timberslide.com:443"
token = "<yourtokenhere>"
```

Contact info@timberslide.com for a token.

## Usage

Send stream

`echo "Hello Timberslide" | ts send hellots`

Receive a stream

`ts get hellots`
