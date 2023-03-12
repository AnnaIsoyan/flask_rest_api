# flask_rest_api
dockerized flask rest api, very simple

#create docker image\n
docker build -t flask-rest-api .

#run docker container from image\n
docker run -dp 5000:5000 flask-rest-api
