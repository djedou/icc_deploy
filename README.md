# pei server

## docker
sudo docker compose pull
sudo docker compose build
docker compose up -d

docker compose up -d --force-recreate
docker compose build --no-cache keycloak

## docker push
docker login

docker push djedou/icc_gateway:tagname // tagname => version
docker push djedou/icc_gateway:tagname