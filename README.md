# Craft CMS 3 (RC-15) + Docker

About CraftCMS : https://github.com/craftcms

## Quickstart
- Configure env: `cp .env.example .env` 
- Start container: `$ docker-compose up -d` 
- Enter container: `$ docker-compose exec php bash` 
    - `$ composer install` 
    - `$ craft install` 
    - `$ craft migrate/up` (optional, generates a homepage & maildev settings)
- Visit: `http://localhost:8084` (/admin to access Craft admin)

You can manage the database : `http://localhost:8085`  
You can view sent mails : `http://localhost:8086`  
You can view logs in : `docker/volumes/nginx`
