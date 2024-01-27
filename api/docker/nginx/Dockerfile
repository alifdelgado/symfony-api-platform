FROM nginx:1.25

ARG UID
EXPOSE $UID

RUN adduser -u ${UID} --disabled-password --gecos "" appuser

COPY default.conf /etc/nginx/conf.d/