FROM busybox
MAINTAINER Chris <c@crccheck.com>

ADD index.html /www/index.html

# Create a basic webserver and sleep forever
CMD httpd -h /www; tail -f /dev/null
