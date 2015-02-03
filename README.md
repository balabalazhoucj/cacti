# cacti
试用于在docker中部署

启动命令：
docker run -v /usr/share/zoneinfo/Asia/Shanghai:/etc/localtime -v $(pwd)/cacti/:/cacti -p 80:80 -it centos:6 /bin/sh
docker#cd /cacti/
docker#sh install.sh
docker #supervisord -c /etc/superversiord.conf
