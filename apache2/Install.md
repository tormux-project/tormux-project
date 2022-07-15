## Apache2 Web Server

### Installation & Setup
```
$ apt update; apt upgrade -y
```
```
$ apt install apache2 -y
```
### Run
```
$ apachectl start
```
![apache2](https://i.ibb.co/ZH9CRvR/apache2.jpg)

### Setup
```
echo "ServerName localhost" >> $PREFIX/etc/apache2/
```

* __Stop apache2___
```
$ apachectl stop
```

* __Run apache2__
```
$ apachectl start
```
