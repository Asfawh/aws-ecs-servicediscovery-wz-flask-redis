FROM python:3.7-alpine
ADD . /code
WORKDIR /code

COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt
RUN pip install redis

CMD ["python", "app.py"]
