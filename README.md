# node-docker-starter
1) Create a directory, go inside the directory
2) npm init #fill in all default to create the package.json with entry point as index.js
3) create file index.js, inside the just add console.log("Hello")
4) Create "Dockerfile" # add the entries as in
5) build docker "docker build -t my-node ."
6) Check the image was created "docker images"
7) Run the container from the image docker run my-node
