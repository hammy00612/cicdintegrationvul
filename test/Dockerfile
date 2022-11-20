
# syntax=docker/dockerfile:1

FROM python:3.8-slim-buster

COPY req.txt .
RUN python -m pip install --upgrade pip
RUN pip install -r req.txt
RUN pip install faraday-cli


ENTRYPOINT ["tail", "-f", "/dev/null"]


