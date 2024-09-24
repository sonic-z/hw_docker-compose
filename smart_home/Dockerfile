FROM python:3.8-alpine
EXPOSE 8000

RUN apk add \
    wget \
    gcc \
    make \
    zlib-dev \
    libffi-dev \
    openssl-dev \
    musl-dev


WORKDIR /opt/smart_home
COPY . .
RUN pip install -r requirements.txt
RUN mkdir /opt/smart_home/static
RUN mkdir /opt/smart_home/media