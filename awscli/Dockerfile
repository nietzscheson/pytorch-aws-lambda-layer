FROM python:3.8.0-alpine

RUN pip3 install --upgrade pip

RUN pip3 install awscli --upgrade --user --no-warn-script-locatio

ENTRYPOINT ["/root/.local/bin/aws"]
