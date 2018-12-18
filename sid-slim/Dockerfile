FROM debian:sid-slim

RUN apt-get update \
    && apt-get install -y --only-upgrade \
    libgnutls30 \
    systemd \
    perl-base \
    libnettle6 \
    --no-install-recommends
