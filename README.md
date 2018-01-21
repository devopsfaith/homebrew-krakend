## Homebrew KrakenD Tap

Install KrakenD API Gateway in your Mac with this tap.

This tap compiles and installs for you the [KrakenD Community Edition](https://github.com/devopsfaith/krakend-ce)

[KrakenD website](http://www.krakend.io)

## Installation

	$ brew tap devopsfaith/krakend
	$ brew install krakend



### Start KrakenD

In order to start KrakenD you will need a configuration file.
Download yours using [KrakenDesigner](http://www.krakend.io/designer/) or get a [sample krakend.json](https://github.com/devopsfaith/krakend-ce/blob/master/krakend.json)

	$ krakend run --config krakend.json -d

More information and documentation: [KrakenD site](http://www.krakend.io)