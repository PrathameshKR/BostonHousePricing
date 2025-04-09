# BostonHousePricing

### Software And Tools Requirements

1. [Github Account](https://github.com)
2. [Heroku Account](https://heroku.com)
3. [VScode IDE](https://code.visualstudio.com/)
4. [Git CLI](https://git-scm.com/book/en/v2/Getting-Strated-The-Command-Line)

Create a new enviornment

```
conda create -p venv python==3.7 -y
```

Activate the enviornment

```
conda activate venv\
```

Create requirements.txt which contains all required libraries, this txt file will be required during deployment to install neccessary libraries


Install all libraries in venv

```
pip install -r requirements.txt
```

Add files to git

```
git add .
```

Commit files to git

```
git commit -m "type msg"
```

Push files to git 

```
git push origin main
```

## Create app.py
Using flask create app which takes input from user for model and then displays the output

## Test the app endpoints using POSTMAN
In postman create json file and check if app works

## Deploy this on render
In render create new web service
Clone this repo and link cloned repo to your web service
and then deploy the web service.
Render will install all neccessary libraries from requirments.txt and then deploy the service



