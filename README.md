# WeST-twitter-crawler
A Logstash-based Twitter crawler powered by Logstash.  

## Requirements
docker and docker-compose

## Usage
1. Create ``.env`` based on ``.env.example`` with your own Twitter app keys.
2. Run ``docker-compose up --build``
3. Open ``localhost:8080`` in a web browser
4. Results shoud be in the ``output`` folder.
