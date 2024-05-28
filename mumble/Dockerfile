# https://github.com/mumble-voip/mumble
FROM ubuntu

RUN apt-get update && apt-get install -y mumble-server

EXPOSE 64738

CMD [ "murmurd", "-fg" ]