# Getting Started - Cheat Sheet
###Use redis for making your spider mush faster

Useful commands below:
1. Clone this project: `git clone https://github.com/MeyiGi/SCRAPY-REDIS.git`
2. https://github.com/python-scrapy-playbook/scaling-python-scrapy-redis/tree/main
3. Create a Python Virtual Environment in the project: `python3 -m venv venv`
4. Activate the Python Virtual Environment: `source venv/bin/activate`
5. Install Scrapy using pip: `pip install scrapy==2.7.0`
6. Install Scrapy using pip: `pip install scrapy-redis`
7. Install Scraoy using pip: `pip install twisted==21.2.0`
8. Add the urls to redis: `python3 add-urls-to-redis.py`
9. Go to the main folder: `cd scrapy-redis`
10. Running the scrapy project: `scrapy crawl scrape_quotes_worker` 


# Signup for a free redis account
You can sign up here: https://redis.com/try-free/

# Update your settings.py and add-ruls-to-redis.py:
Update the REDIS_URL in settings.py with redisClient in add-ruls-to-redis.py to contain your redis details.
It should look something like the following:
`REDIS_URL = 'redis://<username>:<password>@<redis-connection-url>:<redis-port-number>'`
`redisClient = redis.from_url('redis://<username>:<password>@<redis-connection-url>:<redis-port-number>')`





