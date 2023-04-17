FROM python:3.11.3-alpine3.16

USER root

COPY requirements.txt requirements.txt
RUN python3 -m pip install -r requirements.txt
RUN mkdir -p workspaces/test
COPY . workspaces/test/
WORKDIR workspaces/test