FROM jenkins:alpine

MAINTAINER Fabrizio Lungo <docker@flungo.me>

ARG user=jenkins

# Change to root
USER root

# Upgrade to edge branch
RUN sed -i -e 's/v[0-9]\.[0-9]/edge/g' /etc/apk/repositories
RUN apk upgrade --update-cache --available

# Install required packages
RUN apk add --update cloc graphviz

USER ${user}
