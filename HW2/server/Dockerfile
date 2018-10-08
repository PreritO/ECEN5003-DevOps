FROM debian
RUN ["apt-get", "update"]

ENV RESPONSE TEST_RESPONSE
FROM python:3.4-alpine
ADD . /server
WORKDIR /server
CMD ["python", "server.py"]