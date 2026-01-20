sudo docker build -t paruliano/karoseri360_grpc:v1.0.0 .
sudo docker push paruliano/karoseri360_grpc:v1.0.0

sudo docker build -t paruliano/karoseri360_fe:v1.0.0 .
sudo docker push paruliano/karoseri360_fe:v1.0.0

suod docker-compose --env-file .env up -d
