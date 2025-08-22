# Docker-demo-app

Originally from Nana Janashia

Original gitlab repo: https://gitlab.com/nanuchi/techworld-js-docker-demo-app 
YouTube Video: https://www.youtube.com/watch?v=3c-iBn73dDE&t=9626s

#### Commands
```bash
# To build a docker image from the application
docker build -t myapp:2.0 . 
# start the app, mongodb, and mongo-express with 
docker-compose -f mongo.yaml up

# You can access the mongo-express under localhost:8081 from your browser
# You can access the nodejs application under localhost:3000 from your browser
# In mongo-express UI - create a new database "mongo"
# In mongo-express UI - create a new collection "users" in the database "mongo"
```



