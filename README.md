# guacamole-docker

Init Database:

docker run --rm guacamole/guacamole /opt/guacamole/bin/initdb.sh --mysql > initdb.sql
mysql -u username -p database_name < file.sql