FROM onjin/alpine-postgres:latest

MAINTAINER Pierce Moore <me@prex.io>

RUN [ -d /docker-entrypoint-initdb.d ] || mkdir /docker-entrypoint-initdb.d

ADD docker-entrypoint-initdb.d/* /docker-entrypoint-initdb.d
