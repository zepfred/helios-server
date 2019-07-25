FROM nginx:alpine

ADD https://github.com/zepfred/helios-server/archive/master.zip /helios/

WORKDIR /helios/

RUN unzip master.zip

WORKDIR /helios/helios-server-master/

RUN mv ajuda /usr/share/nginx/html

RUN mv ajuda-gestor/ /usr/share/nginx/html

WORKDIR /

RUN rm /helios/helios-server-master/ -Rf
