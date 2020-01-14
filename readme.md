# Deploy to heroku directly

1. Install heroku CLI
2. Command.
```
heroku login
```

3. Requirements for Heroku.
pip install gunicorn
pip freeze > requirements.txt

4. Push to git of heroku
git init
git add . 
git commit -m 'Message'

5. Create heroku app and push to heroku master
heroku create app_name
git remote -v
git push heroku master