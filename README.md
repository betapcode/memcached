# memcached
Hưỡng dẫn 
<br># yum install git
<br># git clone --depth=1 https://github.com/betapcode/memcached.git
<br># cd memcached
<br># mv memcached /etc/init.d/
<br># mv memcached.conf /etc/sysconfig/memcached
<br># mkdir -p /var/run/memcached
<br><p>Tạo user Memcached</p>
<br># chown -R memcached:memcached /var/run/memcached/
<br># cp /usr/local/bin/memcached /usr/bin/
<br># service memcached start
