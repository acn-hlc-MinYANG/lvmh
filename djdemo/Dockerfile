FROM python:3.13-slim
RUN apt-get update && apt-get install -y --no-install-recommends \
    libssl-dev libffi8 libsasl2-dev libldap2-dev libpq5 libjpeg62-turbo zlib1g \
    libxml2 libpcre2-8-0 media-types default-libmysqlclient-dev build-essential pkg-config && \
    rm -rf /var/lib/apt/lists/*
