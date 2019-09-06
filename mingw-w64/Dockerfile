FROM ubuntu:18.04

RUN apt-get update && \
    apt-get install -y gcc-mingw-w64-x86-64 gcc-mingw-w64-i686 nsis

COPY entrypoint.sh /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
