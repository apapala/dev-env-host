# Development Environment - Host

My docker development environment that I use at work and home.

Use this in combine with [dev-env-client](https://github.com/apapala/dev-env-client) for each of your local projects.

## Running
Just run:
```
docker-compose up -d
```

## Services

#### Mailcatcher 
Available at 1080 port 

#### PHPMyAdmin
Available at 8080 port. Use these credentials:
```
server: projectname_mysql
user: root
password: root
```