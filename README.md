# cacti
试用于在docker中部署

启动命令：
docker run -v /usr/share/zoneinfo/Asia/Shanghai:/etc/localtime -v $(pwd)/cacti/:/cacti -p 80:80 -it centos:6 /bin/sh

sh-4.1#cd /cacti/

sh-4.1#sh install.sh

sh-4.1#supervisord -c /etc/superversiord.conf
