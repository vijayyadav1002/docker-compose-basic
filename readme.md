# At the root of the directory

```shell
docker compose build 
docker compose up -d
```

# Update machine hostname like
At -> /etc/hosts in host machine add below line

127.0.0.1      centos7-php8.1.local


# In case you want to run any software inside docker container

```shell
docker compose exec web composer install
```
OR

```shell
docker compose exec web composer update
```

# Note:
> You can add any post launch command in the init.sh file which runs just after docker instance is launched
