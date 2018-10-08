FROM debian
RUN ["apt-get", "update"]
RUN ["apt-get", "install", "iputils-ping"]
ENTRYPOINT ["/bin/ping"]
CMD ["localhost"]
