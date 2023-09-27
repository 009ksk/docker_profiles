# ベースイメージの指定
FROM alpine:latest
# 作業ディレクトリの指定
ENV LANG=C.UTF-8
ENV TZ=Asia/Tokyo

RUN apk update && \
    apk add alpine-sdk cmake clang libressl-dev

WORKDIR /usr/src/apps