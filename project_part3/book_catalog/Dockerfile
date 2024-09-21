# Your Solution

# Dockerfile for book_catalog microservice

FROM python:3.12

WORKDIR /app

COPY ./app/. ./
RUN pip install --no-cache-dir -r requirements.txt


CMD uvicorn main:app --host 0.0.0.0 --port $PORT