
docker build -t <dockerhub-username>/flask-app:latest .



docker run -d -p 5000:5000 <dockerhub-username>/flask-app:latest



docker login


docker push <dockerhub-username>/flask-app:latest
