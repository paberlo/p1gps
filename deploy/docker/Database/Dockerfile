FROM mongo:3.4

MAINTAINER pablo.bermejo@uclm.es

COPY drop/* usr/local/data/db/

CMD ["mongod", "--smallfiles", "--rest"]