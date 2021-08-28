FROM python:3.9.5

RUN pip install \
    django \
    channels \
    channels_redis \
    selenium \
    psycopg2

WORKDIR /api

COPY . .

EXPOSE 8000
