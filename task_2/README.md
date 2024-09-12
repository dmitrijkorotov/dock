docker build . -t my_app:1.0
docker run --name my-app -d -p 5000:5000 my_app:1.0