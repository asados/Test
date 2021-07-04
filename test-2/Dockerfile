# Dockerfile
FROM python:3.8-slim-buster

WORKDIR /app

COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt
CMD [ "pip", "list" ]


#COPY . .
#CMD [ "npm", "start" ]
