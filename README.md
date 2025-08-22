# Docker-demo-app

Originally from Nana Janashia

Original gitlab repo: https://gitlab.com/nanuchi/techworld-js-docker-demo-app 
YouTube Video: https://www.youtube.com/watch?v=3c-iBn73dDE&t=9626s

## Note

This project was done as part of my learning journey with Docker and GitHub.  
I followed Nana Janashia’s tutorial and reproduced the project locally and in Docker.  
I also practiced pushing it to GitHub and connecting it with Azure Container Registry.  

#### Commands
```bash
# To build a docker image from the application
docker build -t myapp:2.0 . 
# start the app, mongodb, and mongo-express with (Add your registry to the image first)
docker-compose -f mongo.yml up

# You can access the mongo-express under localhost:8081 from your browser
# You can access the nodejs application under localhost:3000 from your browser
# In mongo-express UI - create a new database "mongo"
# In mongo-express UI - create a new collection "users" in the database "mongo"
```



