# TODO заменить конфиг /etc/nginx/conf.d/default.conf и добавить 50x.html в соответствии с этим конфигом
FROM nginx:alpine

COPY default.conf /etc/nginx/conf.d/default.conf

COPY 50x.html /usr/share/nginx/html/

EXPOSE 80