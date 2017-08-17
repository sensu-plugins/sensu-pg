# Sensu pg

Sensu pg is package with compiled libpg against sensu openssl. It makes pg gem installation possible in sensu embedded environment. RPM package will be soon.  

___

## Building debian package from source 

1. Clone this repo
```
git clone https://github.com/sensu-plugins/sensu-pg.git
```
2. Install sensu and build-essential pkgs
```
sudo apt-get install sensu build-essential
```
3. Enter in git repo directory
```
cd sensu-pg
```
4. Build debian binary package
```
dpkg-buildpackage -b
```
5. Install package with dpkg

## Install binary package
1. Go to release page
2. Download the newest deb package
3. Install it with dpkg 
