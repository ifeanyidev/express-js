# express-js
Install node and yarn|npm
Install yarn|npm -g install express-generator
Generate express -H express-basic
Install deps cd express-basic/; and yarn|npm install
Run the app DEBUG=express-basic:* npm start
Install npm install -g nodemon
Run nodemon start for reloading in development
Docker image
Run docker build -t node-docker-image .
Run docker run -p 8080:8080 -d --name node-docker node-docker-image
Run docker ps
Go to localhost:8080
Run docker stop node-docker
Run docker start node-docker
