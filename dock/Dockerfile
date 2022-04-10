# syntax=docker/dockerfile:1


FROM python:3
ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=1
WORKDIR /dock
COPY requirements.txt /dock/
RUN pip install -r requirements.txt
COPY . /dock/