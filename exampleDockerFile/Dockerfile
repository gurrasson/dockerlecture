FROM debian/jessie:latest

VOLUME /root/media

EXPOSE 8080

RUN 	apt-get update && \
	apt-get install transmission-daemon -y

CMD /etc/transmission-daemon/transmission-daemon -foreground=true -g -c /var/lib/transmission-daemon/config
