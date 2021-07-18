FROM python:3-alpine

WORKDIR /usr/src/app

COPY . .

RUN pip3 install -r requirements.txt

EXPOSE 8001/tcp

CMD ["python3", "./app.py"]