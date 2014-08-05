squid3-ssl
==========

squid cache ssl dynamic content

1. apt-get install libnetfilter-conntrack3 libltdl7 php5-cli php5 libdb4.8

2. for debian wheezy, download libdb4.8 
wget http://http.us.debian.org/debian/pool/main/d/db4.8/libdb4.8_4.8.30-2_amd64.deb
dpkg -i libdb4.8_4.8.30-2_amd64.deb

3. change  date.timezone php.ini with sed, example :
sed -i 's/;date.timezone =/date.timezone = Asia\/Jakarta/g' /etc/php5/cli/php.ini
