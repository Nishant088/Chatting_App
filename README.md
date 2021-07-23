#Chatting_App

1.


Install all dependencies in root directory

npm install

Install all dependencies in client directory

npm install

2.

Start redis server in new terminal "redis-server"

3.

Create .env file

Env File Content :

------

PORT=2000

BASE_PATH=http://localhost

MONGO_URL=mongodb://localhost:27017/chatapp

MONGO_DB_NAME=chatapp

MONGO_DB_USERS_COLLECTION=users

MONGO_DB_CHATS_COLLECTION=chats

PROFILE_IMAGE_PATH=profiles

AUDIO_PATH=audio

IMAGE_MSG_PATH=attachment

-----

4.

start the server in new terminal "node server.js"

start your react app in new terminal

npm start
