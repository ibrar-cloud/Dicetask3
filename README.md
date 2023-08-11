# Dicetask3

sudo docker volume create my_volume
udo docker volume ls
sudo docker volume inspect my_volume #(details about volume)
sudo docker run -it -d --name conA --mount source=my_volume,target=/apps nginx

sudo docker container inspect conA (view the logs of container)

sudo docker volume rm batman #(remove volume)
