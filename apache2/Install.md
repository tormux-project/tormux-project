## Apache2 Web Server

### Installation
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
echo "ServerName localhost" >> $PREFIX/etc/apache2
```

* __Stop apache2__
```
$ apachectl stop
```

* __Run apache2__
```
$ apachectl start
```

### Port Listening
* Default `port` is `80`
* Install `nano text editor`

```
$ apt install nano
```
```
nano $PREFIX/etc/apache2/httpd.conf
```

* Change the `port 8081`_etc_

![apache-port](https://i.ibb.co/F8JZFKd/apacheport.jpg)

### Save
```
CTRL + X
```
```
Y
```
```
Enter
```

### Web Browser

* Open your `browser`
```
127.0.0.1:8081
```


