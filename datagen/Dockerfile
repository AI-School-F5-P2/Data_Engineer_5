FROM python:3.11

WORKDIR /usr/src/app

RUN pip install --no-cache-dir kafka-python Faker pymongo

COPY . .

CMD [ "python", "./kafka_push.py"]