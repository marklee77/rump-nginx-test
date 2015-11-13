# rump-nginx-test

To start nginx running on a rump kernel:

    docker run -d --cap-add NET_ADMIN -P marklee77/rump-nginx-test

To get the port to connect to and running container name use "docker ps", to
view rump kernel boot information use "docker logs".

