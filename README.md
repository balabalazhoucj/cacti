# cacti
��������docker�в���
�������
docker run -v /usr/share/zoneinfo/Asia/Shanghai:/etc/localtime -v $(pwd)/cacti/:/cacti -p 80:80 -it centos:6 /bin/sh
#cd /cacti/
#sh install.sh
#supervisord -c /etc/superversiord.conf