## Cloudflared Termux

### Installation
```
$ apt update; apt upgrade -y
```
```
$ apt install cloudflared -y
```

* Install `apache2` web server
```
$ apt install apache2 -y
```

### Run
* Apache2 web server
``` 
$ apachectl start
```

* CLoudflared tunnel
```
$ cloudflared http 8080
```

* Your quick `Tunnel` has been `created`! Visit it at (it may take some time to be reachable):

* Copy `trycloudflare.com` url link and paste it in your browser

![cf](https://i.ibb.co/D93Kcmm/cloudflared.jpg)

## Stop

__Cloudflared__
```
CTRL + C
```

__Apache2 server__
```
$ apachectl stop
```
