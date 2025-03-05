# Setup

## Troubleshooting

- I've hit some permission issues with Laravel in WSL. What's going on?
    - I've modified the .env permissions
    - I've also run `sudo chmod -R 777 storage bootstrap/cache`
- [APP_KEY is empty](image.png)
    - I've run `(docker compose exec php-fpm) php artisan key:generate`
- I think the problem is with the setup between WSL Ubuntu and Docker, and we might want a more streamlined solution.