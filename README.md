This image is intended for PHP+MS-SQL development.

## How to run docker image:
```
docker run --name myServer -d -v /your_web_folder:/var/www/html -p 52080:80 tofu0913/ubuntu16php7mysql
```
The command above will expose the HTTP server on port 52080.

## Shell terminal to this docker container
```
docker exec -ti myServer bash
```

Any issue or suggestion, please go to my github: https://github.com/tofu0913/Ubuntu16PHP7MYSQL/issues.
Thanks!
