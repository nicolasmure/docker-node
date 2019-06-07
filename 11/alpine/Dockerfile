FROM node:11.10.0-alpine

RUN echo @edge http://nl.alpinelinux.org/alpine/edge/community >> /etc/apk/repositories && \
    echo @edge http://nl.alpinelinux.org/alpine/edge/main >> /etc/apk/repositories && \
    apk add --no-cache \
      bash \
      ca-certificates \
      curl \
      chromium@edge=~73.0.3683.103 \
      nss@edge=~3.44 \
      freetype@edge=~2.10.0 \
      harfbuzz@edge=~2.5.1 \
      ttf-freefont@edge=~20120503
