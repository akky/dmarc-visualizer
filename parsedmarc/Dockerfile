FROM python:3.9.18-alpine3.19

RUN apk add --update --no-cache libxml2-dev libxslt-dev build-base libffi-dev \
    && pip install parsedmarc 'msgraph-core<1.0.0'

COPY parsedmarc.ini /
#COPY GeoLite2-Country.mmdb /usr/share/GeoIP/GeoLite2-Country.mmdb
