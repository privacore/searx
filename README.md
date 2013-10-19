searx
=====

A hackable [metasearch engine](https://en.wikipedia.org/wiki/Metasearch_engine) respecting privacy.

### Features

* Tracking free
* Modular (see [examples](https://github.com/asciimoo/searx/blob/master/examples))
* Parallel queries
* Supports json output `curl -d 'format=json' -d 'q=searx' http://searx.0x2a.tk/`
* Opensearch support (you can set as default search engine in your browser)
* Search categories

### Installation

* install dependencies: `pip install -r requirements.txt`
* clone source: `git clone git@github.com:asciimoo/searx.git && cd searx`
* edit your [searx/settings.py](https://github.com/asciimoo/searx/blob/master/searx/settings.py) (set your `secret_key`!)
* run `python searx/webapp.py` to start the application

### TODO

* Better ui
* Language support