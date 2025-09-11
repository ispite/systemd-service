# Настройка автоматического запуска Gunicorn через systemd (.service)

https://flask.ivan-shamaev.ru/app-flask-service-wsgi-gunicorn-settings/

sudo systemctl start flaskapp
sudo systemctl enable flaskapp

curl --unix-socket /root/projects/flask-shamaev/flaskapp.sock localhost