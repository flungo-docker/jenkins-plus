FROM jenkins:alpine

MAINTAINER Fabrizio Lungo <docker@flungo.me>

ARG user=jenkins

# Change to root
USER root

RUN apk add --update graphviz

USER ${user}
