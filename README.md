# RubyGarage test task
Before use, you have to install docker-compose

Run command for install your environment:
- docker-compose up -d --build

Install Symfony:  
- docker-compose exec php /bin/bash
- symfony check:requirements
- symfony new .
- composer req --dev maker ormfixtures fakerphp/faker
- composer req doctrine twig
- cp .env .env.local
- DATABASE_URL="mysql://root:secret@database:3306/symfony_docker?serverVersion=8.0"
- symfony console make:entity Product

run http://localhost:8080/