# README

Movie Blog Api

Ruby version '2.5.3'
Rails version '5.2.2'
Postgresql version 2.29.2

To Start the application:

1. docker-compose build
2. docker-compose up -d
3. docker-compose run web rake db:create

To run any command inside container run:
docker exec -it movieblog_web_1 /bin/bash
