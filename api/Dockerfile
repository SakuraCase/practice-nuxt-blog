FROM python:3.6.6
      
ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

ADD . /api
WORKDIR /api
RUN pip install -r requirements.txt