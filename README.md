# RubyGarage test task
Before use, you have to install docker-compose

Run command for install your environment:
- docker-compose up -d --build
- docker-compose run --rm php chown -R $(id -u):$(id -g) .


Install Symfony:  
- docker-compose exec php /bin/bash
- docker-compose exec database /bin/bash

- symfony check:requirements
- symfony new . --version=4.4