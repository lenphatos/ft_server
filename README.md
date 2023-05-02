
# ft_server

The goal of the project is to create Docker image with a server Nginx, phpMyAdmin, MySQL and Wordpress.


## Requirements

- Docker


## Deployment

To deploy this project run

- create the docker image

```bash
  docker build -t "imageName" .
```

- deploy the docker container

```bash
  docker run -d -p 80:80 --name="containerName" "imageName"
```

In your web browser, navigate to ```https://localhost```

You should see the Wordpress configuration page.


## Authors

[@lenphatos](https://www.github.com/lenphatos)

