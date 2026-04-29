
## bygge image
docker build -t docker-side

## kjøre container
docker run -d -p 3000:3000 docker-side

## se liste over alle containere
docker ps

## stoppe containeren
docker stop <containerid>
