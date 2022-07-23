FROM python:3.10.5-slim-buster

WORKDIR /app

COPY requirements.txt .

RUN pip install --requirement requirements.txt

COPY . .
