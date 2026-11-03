FROM jlesage/baseimage-gui:debian-11-v4
ENV DEBIAN_FRONTEND=noninteractive
RUN apt-get update && apt-get install -y --no-install-recommends gparted
ENV APP_NAME="GParted"
ENV USER_ID=0
ENV GROUP_ID=0
RUN printf "#!/bin/sh\nexec gparted\n" > /startapp.sh && chmod +x /startapp.sh
