# Carmen Sandiego (MySQL) setup
__Referenced from [Docs](https://dev.mysql.com/doc/world-setup/en/world-setup-installation.html) and assumes you have MySQL and MySQL Workbench installed__

1. Download data from [here](https://dev.mysql.com/doc/index-other.html) - click `world database` zip file
2. Unzip data file and open Terminal
3. `mysql -u root -p`
4. `mysql> SOURCE <PATH TO FILE>;` e.g. for me in macOS: `mysql> SOURCE ~/Downloads/world-db/world.sql`
5. It's installed. You can find it in MySQL Workbench or `show tables` via cli to explore data. 
