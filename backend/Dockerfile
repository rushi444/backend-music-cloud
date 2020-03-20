FROM python:3.7-alpine
LABEL maintainer="rushi444"

WORKDIR /app/backend

COPY requirements.txt /app/backend

RUN pip3 install --upgrade pip -r requirements.txt

COPY . /app/backend

EXPOSE 8000

CMD python manage.py runserver 0.0.0.0:8000
