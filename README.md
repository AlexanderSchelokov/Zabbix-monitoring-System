Задание 1

#wget https://repo.zabbix.com/zabbix/6.0/debian/pool/main/z/zabbix-release/zabbix-release_6.0-4+debian11_all.deb
#dpkg -i zabbix-release_6.0-4+debian11_all.deb
#apt update
#apt install zabbix-server-pgsql zabbix-frontend-php php7.4-pgsql zabbix-apache-conf zabbix-sql-scripts
#sudo sh -c 'echo "deb http://apt.postgresql.org/pub/repos/apt $(lsb_release -cs)-pgdg main" > /etc/apt/sources.list.d/pgdg.list'
#wget --quiet -O - https://www.postgresql.org/media/keys/ACCC4CF8.asc | sudo apt-key add -
#sudo apt-get update
#sudo apt-get -y install postgresql-13
#sudo -u postgres createuser --pwprompt zabbix
#1234
#sudo -u postgres createdb -O zabbix zabbix
#zcat /usr/share/zabbix-sql-scripts/postgresql/server.sql.gz | sudo -u zabbix psql zabbix
#DBPassword=1234
#systemctl enable zabbix-server apache2


![image](https://user-images.githubusercontent.com/121572590/236664109-2af4a20b-b864-42d4-a610-6ba0f9fd9e27.png)

![image](https://user-images.githubusercontent.com/121572590/236664131-b27fb63c-c155-414b-894c-e1ab50cf150e.png)



Задание 2
#wget https://repo.zabbix.com/zabbix/6.0/debian/pool/main/z/zabbix-release/zabbix-release_6.0-4+debian11_all.deb
#sudo dpkg -i zabbix-release_6.0-4+debian11_all.deb
#apt update
#apt install zabbix-agent
#systemctl restart zabbix-agent
#systemctl enable zabbix-agent

![image](https://user-images.githubusercontent.com/121572590/236665544-0b2d0a2d-c947-4325-b4c8-076b50f6018b.png)



![image](https://user-images.githubusercontent.com/121572590/236665646-dfe7be7c-2853-4566-bc38-eeebcaf9f991.png)

![image](https://user-images.githubusercontent.com/121572590/236665968-6c1b5488-5011-4274-b101-d16dfcbf2a4f.png)


