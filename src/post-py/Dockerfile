FROM python:3.6.0

WORKDIR /app
ADD . /app

RUN pip install --upgrade pip
RUN pip install -r /app/requirements.txt

ENV POST_DATABASE_HOST post_db_test1
ENV POST_DATABASE posts

ENTRYPOINT ["python3", "post_app.py"]
