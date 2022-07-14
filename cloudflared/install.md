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

* Your quick `Tunnel` has been `created`! Visit it at (it may take some time to be reachable):

* Copy `trycloudflare.com` url link and paste it in your browser

# Stop

__Cloudflared__
```
CTRL + C
```

__Apache server__
```
$ apachectl stop
```