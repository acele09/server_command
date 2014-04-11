server_command
==============

postsuper -d ALL defer
varnishd -f /usr/local/varnish/etc/varnish/default.vcl -s malloc,1G -T 127.0.0.1:20001G -T 127.0.0.1:2000
