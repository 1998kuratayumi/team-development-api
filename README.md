## setup

1. Create Docker image

```
$ docker-compose build
```

2. Create Database

```
$ docker-compose run web rails db:create
```

3. Migration Database

```
$ docker-compose run web rails db:migrate
```

4. Setup Container

```
$ docker-compose up
```

5. Access your local environment

```
http://localhost:3000
```