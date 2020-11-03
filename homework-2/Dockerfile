FROM ubuntu:18.04

RUN apt update -y
RUN apt install -y python-pip python-dev

WORKDIR /flask

COPY . /flask

RUN pip --no-cache-dir install -r requirements.txt

EXPOSE 5000

ENTRYPOINT [ "python" ]

CMD [ "app.py" ]
 
