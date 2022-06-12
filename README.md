# jenkins-demo
1. mkdir <name> 
2. create Dockerfile
3. build img and push to repo
    - docker image build -t <userDockerhub>/<name:> .
    - docker image push <userDockerhub>/<name:> 
4. create docker-compose
5. check logs for get password
    - docker container logs <container name>
6. go to  http://localhost:8080
7. choose Install suggested plugins, and wait until Install finished
8. create user, and then click save and finished
