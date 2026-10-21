# Runbook

> Fill in every TODO with exact commands. / Попълнете всяко TODO с точни команди.

## Start locally / Локално стартиране

pip install -r requirements.txt
python -m app.main

## Check that it works / Проверка, че работи

Open:

http://127.0.0.1:8000/health

You should see:

{"status":"ok"}

## Run the tests / Тестове

pytest

## When something breaks / Когато нещо се счупи

Check dependencies:
pip install -r requirements.txt
Start the application and check for errors:
python -m app.main
Run the tests:
pytes

Run with Docker
Build the image
docker build -t notes-api:0.3.0 .

Run the container
docker run -p 8000:8000 notes-api:0.3.0

View logs
docker logs

Stop the container
docker stop