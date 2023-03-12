# machine_learning_project
Start Machine Learning Project

Requirement.

Github Account :
Heroku Account:
VS Code IDE:
GIT CLI:


create a flask app [Hello World]
write a docker file for flask application
create github action for CI/CD
Heroku app for flask deployment
Create structure for ML project
Build Machine Learning Pipeline


Creating conda enviornment
```
conda create -p venv python==3.7 -y
```

```
conda activate venv/
```
OR 
```
conda activate venv
```

```
pip install -r requirements.txt
```


Create a github repoitory

Copy repository from git.
```
git clone https://github.com/tarunbh009/machine_learning_project.git
```

Upload updated code to git:

```
git add . or git add filename
```

To create version/commit all changes by git:

```
git commit -m "comment"
```

To send version/changes to github:

```
git push origin main
```

To check remote url:

```
git remote -v
```

To ignore file or folder from git write the name of file/folder in .gitignore file.

To check git status:

```
git status
```

To check all version maintained by git:

```
git log
```

To setup CI/CD pipeline in heroku we need 3 information
1. HEROKU_EMAIL = anishyadav7045075175@gmail.com
2. HEROKU_API_KEY = <>
3. HEROKU_APP_NAME = ml-regression-app

BUILD DOCKER IMAGE
```
docker build -t <image_name>:<tagname> .
```
> Note: Image name for docker must be lowercase


To list docker image
```
docker images
```

Run docker image
```
docker run -p 5000:5000 -e PORT=5000 f8c749e73678
```

To check running container in docker
```
docker ps
```

Tos stop docker conatiner
```
docker stop <container_id>
```



```
python setup.py install
```


Install ipykernel

```
pip install ipykernel
```
