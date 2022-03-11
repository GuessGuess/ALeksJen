FROM alpine
RUN apk add --no-cache curl wget busybox-extras netcat-openbsd python py-pi
RUN pip install awscli
RUN apk --purge -v del py-pip
CDM tail -f /dev/null