#version 0.0.1 by mr.Burt
FROM python:3
MAINTAINER Albert Timerkhanov <berttimero@gmail.com>
VOLUME git_test
ENV APP /app
RUN mkdir $APP
WORKDIR $APP
EXPOSE 9000
COPY requirements.txt .
RUN pip install -r requirements.txt
COPY . .
CMD ["python","run.py"]