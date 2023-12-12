FROM mcr.microsoft.com/devcontainers/python:1-3.12-bullseye

RUN su -c "pip install --upgrade pip"

COPY requirements.txt /tmp/
RUN su -c "pip install -r /tmp/requirements.txt"
RUN su -c "rm /tmp/requirements.txt"
