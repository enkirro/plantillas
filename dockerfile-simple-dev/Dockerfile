FROM debian:latest

COPY . .

RUN apt update && apt install iputils-ping -y

CMD [ "echo", "Hello World!" ]