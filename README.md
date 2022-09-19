# hm3
Homework #3 for DevOps course
by Temur Pallaev (all sudo's are omitted)

Building an image:
docker build -t hm3-nginx-image:v0.1 .

Running an image:
docker run -d -p 80:80 hm3-nginx-image:v0.1

Retagging local image:
docker tag 122ca25aa0b4 temurp/hm3-nginx-image:0.1

Logging in to docker:
docker login -u "temurp" -p " "

Pushing an image:
docker push temurp/hm3-nginx-image:0.1

Link to dockerhub:
https://hub.docker.com/repository/docker/temurp/hm3-nginx-image

Docker pull:
docker pull temurp/hm3-nginx-image:0.1
