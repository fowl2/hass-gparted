FROM jlesage/baseimage-gui:alpine-3.18-v4
RUN apk add --no-cache gparted e2fsprogs parted bash util-linux
ENV APP_NAME="GParted"
ENV USER_ID=0
ENV GROUP_ID=0
RUN printf "#!/bin/sh\nexec gparted\n" > /startapp.sh && chmod +x /startapp.sh
