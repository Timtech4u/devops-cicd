# Simple Flask App to demo CI/CD using GitHub Actions

## How to run
´´´
python -m pip install flask
python main.py
´´´

## How to build and push a Docker image
´´´
docker build -t mmbello/mywebsite .
docker push mmbello/mywebsite:latest
´´´

## How to run a image
´´´
docker run -p 8080:8080 mmbello/mywebsite:latest 
´´´










