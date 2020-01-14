pip install gunicorn
pip freeze > requirements.txt

git init
git add . 
git commit -m 'Message'

heroku create app_name
git remote -v
git push heroku master