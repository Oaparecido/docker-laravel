# Docker for application with composer

In this repository you find files that build applications with [composer](https://getcomposer.org/)

### Here you can find:
* [`PHP 8`](https://www.php.net/releases/8.0/en.php) **(Alpine version)**
* [`Ngnix 1.19`](https://www.nginx.com/) **(Alpine version)**
* [`MySQL 5.7`](https://www.mysql.com/) **(Complete version)**
* [`PHPMyAdmin`](https://www.phpmyadmin.net/) **(Complete version)**

### Ports that are exposed:
* `:9001` - Access PHPMyAdmin.
* `:3307` - Access MySql **(DB)**.
* `:3003` - Access application with Nginx.

### How to run:
To run this docker file you **only** need the ```docker``` and the ```docker-compose``` installed.

**To install follow the tutorials**
<br>
```docker``` - [How to install docker](https://docs.docker.com/engine/install/)
<br>
```docker-compose``` - [How to install docker-compose](https://docs.docker.com/compose/install/)

**Commands:**
<br>
`docker-compose up -d` - Execute in a directory tha have file docker-compose.yml.

How to run **into container**:
<br>
`docker-compose exec` - Execute before the commands for laravel.
<br>
`composer create-project --prefer-dist laravel/laravel name` - For build application **Laravel**.


### VOILA, You have a application in docker!