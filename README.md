server_command
==============

メールキュー削除
postsuper -d ALL defer
varnish起動
varnishd -f /usr/local/varnish/etc/varnish/default.vcl -s malloc,1G -T 127.0.0.1:20001G -T 127.0.0.1:2000
開発起動
rails s -d -p 18000
Apache再起動
sudo service httpd restart

varnish設定
/usr/local/varnish/etc/varnish/default.vcl
Apache設定
/etc/httpd/conf/httpd.conf
