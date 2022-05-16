# Laravel 9 Docker Setup ✨

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://crew-code.com/docker-setup-for-laravel-application)&nbsp;[![Build passing](https://img.shields.io/badge/Build-Passing-brightgreen.svg?style=flat-square)](https://crew-code.com/docker-setup-for-laravel-application)&nbsp;[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=102)](https://crew-code.com/docker-setup-for-laravel-application)&nbsp;[![License](https://img.shields.io/badge/license-MIT-brightgreen)](https://crew-code.com/docker-setup-for-laravel-application)&nbsp;![Made with Love in India](https://madewithlove.org.in/badge.svg)

Docker setup for Laravel application with docker compose, it will help in quick start your laravel project and helps in setting up your laravel dev environment without any extra burden of installing any software and packages in to your computer just clone the project and run some basic docker command and you are done and you can start working on your laravel project

**Demo Youtube Video** - ***https://www.youtube.com/watch?v=muiw4egRSN8***

**Demo Blog link** - ***https://crew-code.com/docker-setup-for-laravel-application/***

## Features and Functionalities 😃

- Docker setup for Laravel, MySql, PHP 8, Laravel compose
- Docker compose file to combine everything together
- MySQL for database

## Screenshots

### Nginx server file

![nginx](https://drive.google.com/uc?export=view&id=1aD6Ie5s6DycW5wiDQlg27CDO7Vrg0ztt)

### Php Docker File

![enter image description here](https://drive.google.com/uc?export=view&id=1G9tNqyAOxHq_hLC7KAgc8PzMLabaniVW)

### MySql env file

![enter image description here](https://drive.google.com/uc?export=view&id=10Zzd1ome_uGpYFh4i_m5T8CfHQTaBU6p)

### Composer docker file

![enter image description here](https://drive.google.com/uc?export=view&id=1o2q_dwo3F8Rp56hlc4_RAmY__mHPy56-)

## Tech Stack 💻

- [Laravel](https://laravel.com/)
- [MySql](https://www.mysql.com/)
- [Php](https://www.php.net/)
- [Docker Compose](https://docs.docker.com/compose/)
- [Docker](https://www.docker.com/)

## Installation and Running App :zap:

**1. Clone this repo by running the following command :-**

```bash
 git clone https://github.com/CrewCodeAnku/Laravel-Docker-Setup.git
 cd Laravel-Docker-Setup
```

**2. Make sure your docker is up and running in your computer**

**3. Now run the docker command to create laravel project :-**

```bash
 docker-compose run --rm composer create-project --prefer-dist laravel/laravel .
```

**3. Update Laravel project .env file :-**

```bash
 DB_HOST = mysql;
DB_DATABASE = homestead;
DB_USERNAME = homestead;
DB_PASSWORD = secret;
```

**4. Run below command to start php, mysql and server container :-**

```bash
 docker-compose up -d --build server
```

**4.** **🎉 Open your browser and go to `http://localhost:8000`**

## 🤩 Don't forget to give this repo a ⭐ if you like this repo and want to appreciate our efforts

[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/built-by-developers.svg)](https://forthebadge.com)
