# WeST-twitter-crawler
A Logstash-based Twitter crawler developed by UNIKO, based on the [Twitter Stream API](https://developer.twitter.com/en/docs/tweets/filter-realtime/overview), unlike the previously developed [search-API-based crawler](https://github.com/CUTLER-H2020/DataCrawlers/tree/master/Social/twitterCrawler).  
It provides a Web-based user interface that allows users to manage their keywords.

## Requirements
docker and docker-compose

## Usage
1. Create ``.env`` based on ``.env.example`` with your own Twitter app keys.
2. Run ``docker-compose up --build``
3. Open ``localhost:8080`` in a web browser
4. Results shoud be in the ``output`` folder.
