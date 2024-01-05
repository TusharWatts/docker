# docker-local-project

Run the docker as:

docker run -v ${pwd}/src:/app/src  -p 4000:3000 -it --init <img-name>

docker run -it --init -v ${pwd}:/developer/app -v volume-node-modules:/developer/app/node_modules  -p 4000:3000 <img-name>