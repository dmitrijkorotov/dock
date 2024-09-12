docker build . -t my-nginx<br />
docker run --name some-nginx -d -p 8088:80 my-nginx