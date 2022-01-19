# TorScraper [![Build Status](https://travis-ci.com/webfp/tor-browser-selenium.svg?branch=main)](https://travis-ci.com/webfp/tor-browser-selenium)

Install `geckodriver` from the [geckodriver releases page](https://github.com/mozilla/geckodriver/releases/). Make sure you install version v0.26.0 version or newer; older versions may not be compatible with the current Tor Browser series.

## Basic usage
### Using with system `tor`

TorBrowserDriver does not download Tor Browser Bundle (TBB) for you. You should [download](https://www.torproject.org/projects/torbrowser.html.en), extract TBB and provide its path when you initialize `TorBrowserDriver`.


## Script

After installing all the necessary libreires and packages, you can try out the two scripts in python.

The first [script](https://github.com/LeonardRanaldi/TorScraper/blob/main/scraper.py) is a basic version of the scraper where a function is implemented that takes a '.onion' link as input and writes the text in the service into a text file.

The second [script](https://github.com/LeonardRanaldi/TorScraper/blob/main/torVerScraper.py) extends the functions of the first script and provides new functions to extract new '.onion' links.


## Note!

If you would like to consult `BERT in the Dark Web needs KERMIT eyes` . (as written in my CV)


