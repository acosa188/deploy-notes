# How to deploy a node application to Heroku

## Make sure that in your root folder you have your Procfile
## Make sure that you already initialize git repository
https://github.com/

## Log in to your heroku account and go to apps section
https://dashboard.heroku.com/apps

## Then click the 'New' button on the top right corner
- Click the 'Create new app'
- Name it want you want
- Click create app button

## In your command line or VS Code command line
- log in to heroku by running this command
<br>

``` 
heroku login 
```
- then connect git repo to heroku
<br>

``` 
heroku git:remote -a ${heroku-application-name}
```

- then add any commits
```
git add .
git commit -m "any message here"
```
- then push it to main
```
git push heroku main
```

## You are good to go, happy coding!!!
