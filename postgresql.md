To use the apt repository, follow these steps: 
```
sudo sh -c 'echo "deb https://apt.postgresql.org/pub/repos/apt $(lsb_release -cs)-pgdg main" > /etc/apt/sources.list.d/pgdg.list'
```
```
wget --quiet -O - https://www.postgresql.org/media/keys/ACCC4CF8.asc | sudo apt-key add -
```
```
sudo apt-get update
```
```
sudo apt-get -y install postgresql
```
to log as psql superuser
``` 
sudo -u postgres psql   
```
|description|command|
|---|---|
|to create a DB|CREATE DATABASE mabdd OWNER bob;|
|to create a user|CREATE USER bob WITH PASSWORD 'monmdp';|
|to alter a user|ALTER USER bob CREATEDB;|



