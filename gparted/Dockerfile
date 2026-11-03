FROM jlesage/baseimage-gui:ubuntu-22.04-v4
RUN apt-get update && apt-get install -y gparted
ENV APP_NAME="GParted"
ENV USER_ID=0
ENV GROUP_ID=0
RUN printf "#!/bin/sh\nexec gparted\n" > /startapp.sh && chmod +x /startapp.sh
