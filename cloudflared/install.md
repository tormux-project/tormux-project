## Cloudflared Termux

### Installation
```
$ apt update; apt upgrade -y
```
```
$ apt install apache2 cloudflared -y
```

### Run
``` 
$ apachectl start
```
```
$ cloudflared http 8080
```


![cf](https://i.ibb.co/D93Kcmm/cloudflared.jpg)
