## Description

PyWeather is a script for displaying the current weather conditions in your terminal, with support for ANSI colors and Unicode symbols. It originated as a Python port of AnsiWeather, which is developed by Frederic Cambus and can be found here: https://github.com/fcambus/ansiweather; however, PyWeather's status as an exact derivative of AnsiWeather is no longer ongoing. It is currently experimental and may deviate from the original repo, although new commits and concepts may still be adopted at any time.

![PyWeather Screenshot](http://oi43.tinypic.com/swtouo.jpg)

Weather data comes from the `OpenWeatherMap` free weather API.

## Requirements

PyWeather requires the following dependency: 

- Python 2.7

The intent in creating PyWeather is to offer an alternative which has only one dependency: Python. A standard Python installation (which is prevalent and offered on OS X and almost any other *nix box) is all that is needed.

It should also work on Windows, although there is currently no support for Unicode and console colors.

## Usage

	./pyweather [-u imperial|metric|kelvin] [-t] city[,country]

Use the '-t' flag to disable symbols.

The final argument, which is required, can be done in a numerous amount of ways. The country or country code is usually optional, but will help the weather API reduce ambiguity.

You can also discard the country or country code, as the script now prints out the name of the country.

For example:

	./pyweather -u metric "New York" "Beijing" "London" "Rome,IT"

## Contributing

Help contribute to PyWeather by starring the repo, sharing it, submitting a pull request or posting an issue! :)

## License

PyWeather is released under the BSD 3-Clause license (which AnsiWeather is released under). See `LICENSE` file for details.
