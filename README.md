// with docker-compose.yaml file
docker compose build
docker compose up
docker ps
docker ps -a
docker rm containerid
docker compose down
mongo --port 2717
https://youtu.be/vm3YfOHf_Cc


// without docker-compose.yaml file
docker login bharathpersonal7898
docker build . -t bharathpersonal7898/reponame
So if we wanted to expose port 3000 inside the container to port 49160 outside the container, we would pass 49160:3000 to the --publish flag.
docker run -p 49160:3000 -d bharathpersonal7898/reponame
In browser hit this url http://localhost:49160/products
docker exec -it d7629a08004cc3276545998e1f39fd8629112fc58e608c8943268890a63358b0 /bin/bash
docker logs d7629a08004cc3276545998e1f39fd8629112fc58e608c8943268890a63358b0
docker ps -a
docker stop d7629a08004c
docker images
docker push bharathpersonal7898/reponame
https://nodejs.org/en/docs/guides/nodejs-docker-webapp/
