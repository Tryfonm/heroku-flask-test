1) create a 'Procfile':
```
web: gunicorn app:app
```

2) push on github

3) log in heroku with:
```
heroku login
```

4) create the app with:
```
heroku create {name of the app}
```

5) deploy the app with:
```
git push heroku main
```

6) Useful commands:
```
heroku open
heroku logs
```