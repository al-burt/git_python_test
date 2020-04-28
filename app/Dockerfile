#version 0.2.1 by mr.Burt
FROM python:3 as build-stage
MAINTAINER Albert Timerkhanov <berttimero@gmail.com>

COPY . /app
WORKDIR /app

RUN pip install -r requirements.txt

EXPOSE 9000:9000

ENTRYPOINT python run.py