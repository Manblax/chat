FROM python:3.9.5

RUN pip install \
    django \
    channels \
    channels_redis

WORKDIR /api

COPY . .

EXPOSE 8000
