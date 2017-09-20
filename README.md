# docker-botpress
Docker image for Botpress (https://botpress.io/)

## Usage

### Initialize a new bot

`docker run --rm -it -v my-bot-dir:/data jtdoepke/botpress init`


### Run a bot

`docker run -d -p 3000:3000 -v my-bot-dir:/data jtdoepke/botpress`

### To Stop a bot

`docker ps 

`docker stop [container_name]

### To install botpress-platform-webchat

Make sure your container is running

`docker exec -it [container-name] npm install botpress-platform-webchat

Once the package is successfully installed , stop the docker container , start the bot and then run it

`docker run --rm -it -v my-bot-dir:/data jtdoepke/botpress start
`docker run -d -p 3000:3000 -v my-bot-dir:/data jtdoepke/botpress
