# hm3
### Homework #3 for DevOps course
**_by Temur Pallaev (all sudo's are omitted)_**


Building an image:
```sh 
docker build -t hm3-nginx-image:v0.1 . 
```

Running an image:
```sh 
docker run -d -p 80:80 hm3-nginx-image:v0.1 
```

Retagging local image:
```sh
docker tag 122ca25aa0b4 temurp/hm3-nginx-image:0.1
```

Logging in to docker:
```sh
docker login -u "temurp" -p " "
```

Pushing an image:
```sh
docker push temurp/hm3-nginx-image:0.1
```

Docker pull:
```sh
docker pull temurp/hm3-nginx-image:0.1
```

Link to dockerhub:
_https://hub.docker.com/repository/docker/temurp/hm3-nginx-image_
