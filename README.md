# Sentry in docker

    echo "SENTRY_SECRET_KEY=$(openssl rand -hex 32)" > .env
    docker-compose --rm sentry sentry upgrade
    docker-compose up
