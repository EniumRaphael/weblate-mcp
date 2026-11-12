FROM alpine:latest

RUN apk add --no-cache git pnpm npm bash

ENV EDITOR=vim

RUN addgroup -g 1000 dev
RUN adduser -u 1000 -G dev -s /bin/bash -D dev
