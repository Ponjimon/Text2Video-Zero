FROM alpine:3.17
# FROM python:3.11-bullseye

# RUN DEBIAN_FRONTEND=noninteractive apt-get update && apt-get -y install --no-install-recommends \
#     build-essential \
#     python3-dev \
#     python3-setuptools \
#     make \
#     cmake
# RUN DEBIAN_FRONTEND=noninteractive apt-get update && apt-get -y install --no-install-recommends \
#     ffmpeg \
#     libavcodec-dev \
#     libavfilter-dev \
#     libavformat-dev \
#     libavutil-dev
# RUN git clone --recursive https://github.com/dmlc/decord
# RUN cd decord \
#     && mkdir build \
#     && cd build \
#     && cmake .. -DUSE_CUDA=0 -DCMAKE_BUILD_TYPE=Release \
#     && make
# RUN cd ../python \
#     && python3 setup.py install --user