# Getting Started - Cheat Sheet 📜
### Use redis for making your spider much faster 👺

Useful commands below✅:
1. Clone this project: `git clone https://github.com/MeyiGi/SCRAPY-REDIS.git`
2. Create a Python Virtual Environment in the project: `python3 -m venv venv` 
3. Activate the Python Virtual Environment: `source venv/bin/activate` 
4. Install Scrapy using pip: `pip install scrapy==2.7.0` 
5. Install Redis using pip: `pip install scrapy-redis`
6. Install Twisted using pip: `pip install twisted==21.2.0`
7. Go to the main folder: `cd scrapy-redis`
8. Add the urls to redis: `python3 add-urls-to-redis.py`
9. Running the scrapy project: `scrapy crawl scrape_quotes_worker` 

❗Be sure! Install only this versions!

# Signup for a free redis account👾
You can sign up here: https://redis.com/try-free/

# Update your "settings.py" and "add-uls-to-redis.py"⚙️:
Update the REDIS_URL in settings.py with redisClient in add-ruls-to-redis.py to contain your redis details.
It should look something like the following: < br />
`REDIS_URL = 'redis://<username>:<password>@<redis-connection-url>:<redis-port-number>'` < br />
`redisClient = redis.from_url('redis://<username>:<password>@<redis-connection-url>:<redis-port-number>')`

## Screenshots 🤳

![Снимок экрана 2024-06-14 094627](https://github.com/MeyiGi/SCRAPY-REDIS/assets/130828110/928e6739-93af-47a6-a526-c566e3517479)  👉👉👉👉👉 ![Снимок экрана 2024-06-14 101704](https://github.com/MeyiGi/SCRAPY-REDIS/assets/130828110/da663a6a-043d-43a6-a058-241a7fcf730f)

![Снимок экрана 2024-06-14 101807](https://github.com/MeyiGi/SCRAPY-REDIS/assets/130828110/7d85d006-023d-40d2-b2ea-72022516a269)


