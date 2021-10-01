# TorScraper [![Build Status](https://travis-ci.com/webfp/tor-browser-selenium.svg?branch=main)](https://travis-ci.com/webfp/tor-browser-selenium)

Install `geckodriver` from the [geckodriver releases page](https://github.com/mozilla/geckodriver/releases/). Make sure you install version v0.26.0 version or newer; older versions may not be compatible with the current Tor Browser series.

## Basic usage
### Using with system `tor`

TorBrowserDriver does not download Tor Browser Bundle (TBB) for you. You should [download](https://www.torproject.org/projects/torbrowser.html.en), extract TBB and provide its path when you initialize `TorBrowserDriver`.


