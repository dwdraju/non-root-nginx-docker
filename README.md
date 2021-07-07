# Nginx Docker With Non-root User
For least privilege user, its better to use non-root user. This is simple example of creating docker image where nginx runs with limited privilege user.

## To Create Image and Run
```
docker build -t app
docker run -d app

```
