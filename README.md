# TorScraper [![Build Status](https://travis-ci.com/webfp/tor-browser-selenium.svg?branch=main)](https://travis-ci.com/webfp/tor-browser-selenium)


**Paper**: https://arxiv.org/abs/2201.05613


## Basic usage
### Using with system `tor`

Install `geckodriver` from the [geckodriver releases page](https://github.com/mozilla/geckodriver/releases/). Make sure you install version v0.26.0 version or newer; older versions may not be compatible with the current Tor Browser series.


TorBrowserDriver does not download Tor Browser Bundle (TBB) for you. You should [download](https://www.torproject.org/projects/torbrowser.html.en), extract TBB and provide its path when you initialize `TorBrowserDriver`.


## Script

After installing all the necessary libreires and packages, you can try out the two scripts in python.

The first [script](https://github.com/LeonardRanaldi/TorScraper/blob/main/scraper.py) is a basic version of the scraper where a function is implemented that takes a '.onion' link as input and writes the text in the service into a text file.

The second [script](https://github.com/LeonardRanaldi/TorScraper/blob/main/torVerScraper.py) extends the functions of the first script and provides new functions to extract new '.onion' links.



# Citation
If you use this code, please cite the paper:
```
@misc{ranaldi2022dark,
      title={The Dark Side of the Language: Pre-trained Transformers in the DarkNet}, 
      author={Leonardo Ranaldi and Aria Nourbakhsh and Arianna Patrizi and Elena Sofia Ruzzetti and Dario Onorati and Francesca Fallucchi Fabio Massimo Zanzotto},
      year={2022},
      eprint={2201.05613},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```


## Note!

If you would like to consult `BERT in the Dark Web needs KERMIT eyes` . (as written in my CV)

