# docker-compose-environment-variables-demo

printenv
export SECRET_ENV=my_secret_value
printenv | grep SECRET_ENV
flask run
sudo docker compose down
sudo docker compose up
sudo docker run --env-file ./.env --rm -p 8000:5000 <image-name>

