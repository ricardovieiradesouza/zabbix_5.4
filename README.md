# zabbix_5.4

https://www.zabbix.com/download?zabbix=5.4&os_distribution=red_hat_enterprise_linux&os_version=8&db=mysql&ws=nginx


Adicionado o usuario mysqladmin sem senha para monitoramento:

/etc/my.cnf.d/client.cnf


[client]
password = password

# This group is not read by mysql client library,
# If you use the same .cnf file for MySQL and MariaDB,
# use it for MariaDB-only client options
[client-mariadb]
