# livecoin-scrapy-splash

This program uses scrapy-splash module to render the webpage with js in it and parse the data. A lot faster approach than using selenium. 
Install docs can be found here: https://github.com/scrapy-plugins/scrapy-splash and https://splash.readthedocs.io/
Execute script using: scrapy crawl coin.py

To save the data on a file use the -o flag like so: scrapy crawl coin.py -o coin.json
