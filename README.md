# Link Shortener Django

## Table of Contents

* [Getting Started](#getting-started)
  + [Using Docker](#using-docker)

## Getting Started

### Using Docker

- Clone the repo

```
git clone https://github.com/aerabi/link-shortener
```

- Bring up the app

```
docker-compose up -d --build
```

- Perform the migration

```
docker-compose exec web python manage.py migrate
```