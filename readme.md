# README

## Create a docker image
```docker build -t simple-django-on-docker -f Dockerfile .```

## Rnn the docker image
```docker run -it -p 8000:8000 simple-django-on-docker```

## Stop and delete a docker image 
```docker stop containerID && docker rm containerID```

