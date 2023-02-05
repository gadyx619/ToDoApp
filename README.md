How to install:

1. Inside backend

npm install
2. Change directory to frontend

cd frontend
3. Inside frontend directory

npm install
How to run: You need to have two cmd prompts open for both main directory and frontend directory

In main backend:

npm start
In frontend directory:

npm start

create a .env file and add the following parameter inside backend folder
PORT = 5001
MONGO_URL ="mongodb://gadyx:Test123@ac-deeppzu-shard-00-00.52a900t.mongodb.net:27017,ac-deeppzu-shard-00-01.52a900t.mongodb.net:27017,ac-deeppzu-shard-00-02.52a900t.mongodb.net:27017/?ssl=true&replicaSet=atlas-j82krp-shard-0&authSource=admin&retryWrites=true&w=majority"