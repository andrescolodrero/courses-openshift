FROM python:3.8-slim-buster

WORKDIR /app

COPY readme.txt readme.txt
RUN pip3 install -r readme.txt

COPY . .

CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0"]