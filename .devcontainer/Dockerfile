FROM python:3.11-bullseye

RUN DEBIAN_FRONTEND=noninteractive apt-get update && apt-get -y install --no-install-recommends \
    build-essential \
    python3-dev \
    python3-setuptools \
    make \
    cmake
RUN DEBIAN_FRONTEND=noninteractive apt-get update && apt-get -y install --no-install-recommends \
    ffmpeg \
    libavcodec-dev \
    libavfilter-dev \
    libavformat-dev \
    libavutil-dev