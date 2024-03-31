FROM steamcmd:latest 

LABEL maintainer="dmitry.smosk@yandex.ru"

RUN ./steamcmd.sh 
RUN +force_install_dir /home/steam/squad-dedicated +login anonymous +app_update 403240 +quit

WORKDIR /server
VOLUME /server