## Description

PyWeather is a script for displaying the current weather conditions in your terminal, with support for ANSI colors and Unicode symbols. It is a Python port of AnsiWeather, which is developed by Frederic Cambus and can be found here: https://github.com/fcambus/ansiweather.

![PyWeather Screenshot](http://oi43.tinypic.com/swtouo.jpg)

Weather data comes from the `OpenWeatherMap` free weather API.

## Requirements

PyWeather requires the following dependency: 

- Python 2.7

The intent in creating PyWeather is to offer an alternative which has only one dependency: Python. A standard Python installation (which is prevalent and offered on OS X and almost any other *nix box) is all that is needed.

## Usage

	./pyweather [-u imperial|metric|kelvin] [-t] city[,country]

Use the '-t' flag to disable symbols.

The final argument, which is required, can be done in a numerous amount of ways. The country or country code is usually optional, but will help the weather API reduce ambiguity.

For example:

	./pyweather -u metric "New York,NY" "Beijing,CN" "London,UK"

## Contributing

Help contribute to PyWeather by submitting a pull request or posting an issue! :)

## License

PyWeather is released under the BSD 3-Clause license (which AnsiWeather is released under). See `LICENSE` file for details.
