## Description

PyWeather is a script for displaying the current weather conditions in your terminal, with support for ANSI colors and Unicode symbols. It is a Python port of AnsiWeather, which is developed by Frederic Cambus and can be found here: https://github.com/fcambus/ansiweather.

![PyWeather Screenshot](http://oi43.tinypic.com/swtouo.jpg)

Weather data comes from the `OpenWeatherMap` free weather API.

## Requirements

PyWeather requires the following dependency: 

- Python 2.7

The intent in creating PyWeather is to offer an alternative which has only one dependency: Python. A standard Python installation (which is prevalent and offered on OS X and almost any other *nix box) is all that is needed.

## Usage

After cloning the repository, simply invoke the script by typing:

	./pyweather

## Configuration

The following configuration options are available and should be set according to your location and preferences.

Config options can also be set in ~/.pyweatherrc

Example : `~/.pyweatherrc`

	[main]
	location: New York,NY
	units: metric
	symbols: yes

	[colors]
	...

	[icons]
	...

Other options can be found in the script; they are easy to set and self-explanatory.

## License

PyWeather is released under the BSD 3-Clause license (which AnsiWeather is released under). See `LICENSE` file for details.
