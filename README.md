co# machine_learning_pipeline
## This is a demo project for end-to-end
### Required software


1. [Github Account](https://github.com/)
2. [Heroku Account](https://id.heroku.com/login)
3. [VS Code IDE](https://code.visualstudio.com/download#)
4. [Git Cli](https://git-scm.com/download/win)
5. [Git Documentation](https://git-scm.com/docs/gittutorial)


Creating conda envionment
....
conda create -p venv python==3.7 -y
....

conda activate venv/
....

conda init (shell_name).exe
....


To add files in git 

git add .
....
or,

git add <filename>
...

To igrone file or folder from git we can write name of 
file/folder in .gitignore file
...

To send version/changes to github
...

git push origin main
...

To check remote url
...

git remote -v
...

To setup CI/CD pipeline in heroku we need 3 information

1.Heroku_Email=souradeeproy.10@gmail.com

2.Heroku_API_KEY=0e97e7b8-1286-4d6c-a2f1-f18299126b81

3.HEROKU_APP_NAME=ml-ops-housing


BUILD DOCKER IMAGE
...

docker build -t <image_name>:<tag_name> .
...
>Note: Image name for docke must be in lowercase


To list docker images
...
docker images
...

Run docker image
...
docker run -p 5000:5000 -e PORT=5000 <image_id>
...

To check running containers in docker
...
docker ps
...
To stop docker container
...
docker stop <container_id>
...
