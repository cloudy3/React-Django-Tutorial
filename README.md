
# Full Stack Web App using Spotify's API

## _Setup Instructions_

### Install Required Python Modules

```bash
pip install django
pip install djangorestframework
```
### Start Web Server

Run the django web server.
```bash
py .\manage.py runserver
```

### Install Node Modules

First cd into the ```frontend``` folder.
```bash
cd frontend
```
Next install all dependicies.
```bash
npm i
```

### Compile the Front-End

Run the production compile script
```bash
npm run build
```
or for development:
```bash
npm run dev
```


## _Creating The Files_
```bash
django-admin startproject <project_name>
cd .\<project_name>\
django-admin startapp <folder_name>
```
Then add app into installed apps of settings.py.
Add 'rest_framework" into installed apps.

### Making Migrations
```bash
py .\manage.py makemigrations
py .\manage.py migrate
```

### Initialising Front-End Folder
```bash
npm init -y
npm i webpack webpack-cli --save-dev
npm i @babel/core babel-loader @babel/preset-env @babel/preset-react --save-dev
npm i react react-dom --save-dev
npm install @material-ui/core
npm install @babel/plugin-proposal-class-properties
npm install react-router-dom
npm install @material-ui/icons
```
