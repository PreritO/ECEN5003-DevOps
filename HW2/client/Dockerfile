FROM debian
RUN ["apt-get", "update"]

ENV INTERVAL 1
FROM python:3.4-alpine
ADD . /client
WORKDIR /client
CMD ["python", "client.py"]