FROM nextcloud:apache

RUN apt-get update \
    && apt-get install -y --only-upgrade linux-libc-dev \
    && dpkg-query -W linux-libc-dev \
    && rm -rf /var/lib/apt/lists/*