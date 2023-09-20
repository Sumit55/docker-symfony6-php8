# Dockerize symfony6 + php 8 + mysql + ngnix + node
Fast lightweight Docker network using PHP MySQL Nginx and Node

# Installation

- Clone this repo

- Run ```docker-compose build ```

- Run ```docker-compose up -d ```

- Go instide php container ```docker exec -it php81-container bash```

- Create project  ```composer create-project symfony/skeleton:"6.2.*" . ```

- Hit ```http://localhost:8085/```