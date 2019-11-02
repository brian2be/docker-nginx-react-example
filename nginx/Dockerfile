FROM nginx:1.14-alpine
ENV LANG=C.UTF-8 LC_ALL=C.UTF-8

RUN apk update && apk add --no-cache \
  vim \
  net-tools \
  iputils \
  curl \
  busybox-extras \
  && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*

WORKDIR /etc/nginx/
ADD conf.d /etc/nginx/conf.d/

CMD ["nginx", "-g", "daemon off;"]