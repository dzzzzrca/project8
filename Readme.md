# Generating random words
https://wonderwords.readthedocs.io/en/latest/quickstart.html#the-randomsentence-class

# How to
1. Run `python -m venv env` to create virtual environment
2. Run `pip install -r requirements.txt` to install Python packages
3. Run `docker-compose up` to spin up Kafka broker
4. Run `python sentences_producer.py` to run the producer to produce data
5. Run `python analytics.py` to get the data stream from Kafka and run the sentiment analysis

![Screenshot (409)](https://github.com/dzzzzrca/project8/assets/153365739/19eaa5cb-37c6-416f-8639-3b50ac27a9de)
