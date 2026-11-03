FROM jlesage/baseimage-gui:alpine-3.18-v4
RUN apk add --no-cache gparted e2fsprogs parted
ENV APP_NAME="GParted"
RUN printf "#!/bin/sh\nexec /usr/sbin/gparted\n" > /startapp.sh && chmod +x /startapp.sh
