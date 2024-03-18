docker-compose run --rm sentry-base config generate-secret-key
docker-compose run --rm sentry-base upgrade
docker-compose up -d