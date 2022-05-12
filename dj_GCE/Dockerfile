FROM python:3.8
ENV PYTHONNUMBERFUFFERED 1
RUN mkdir /code
WORKDIR /code
ADD requirements.txt /code/
#COPY requirements.txt /code/
RUN apt-get update
RUN apt-get install -y vim
RUN pip install -r requirements.txt
ADD . /code/