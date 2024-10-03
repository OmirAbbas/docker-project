FROM python:3.10-alpine

WORKDIR /code

COPY requirements.txt .

RUN pip install -r requirements.txt

EXPOSE 5000

COPY . .

CMD [ "python","app.py" ]