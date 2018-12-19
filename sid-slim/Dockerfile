FROM debian:sid-slim

RUN apt-get update \
    && apt-get install -y --only-upgrade \
    libgnutls30 \
    libsystemd0 \
    libudev1 \
    perl-base \
    libnettle6 \
    tar \
    --no-install-recommends \
    && rm -rf /var/lib/apt/lists/*
