FROM rust

ENV MYSQL_LOGIN_PASS=${MYSQL_LOGIN_PASS}

EXPOSE 8080

RUN mkdir /app
WORKDIR /app

RUN apt update -y && apt upgrade -y

ENTRYPOINT
