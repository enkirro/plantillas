FROM python:3.13-alpine

WORKDIR /app

RUN apk update

COPY requirements.txt requirements.txt

COPY app.py app.py

RUN pip install --upgrade pip

RUN pip install -r requirements.txt

CMD [ "python", "app.py" ]