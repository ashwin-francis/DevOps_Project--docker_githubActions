pip3 install -r requirements.txt


python3 app.py runserver


docker build . -t flaskdemo

docker run -d -p 80:5000 flaskdemo