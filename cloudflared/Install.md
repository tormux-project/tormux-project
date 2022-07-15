## Cloudflared Termux

### Installation
```
$ apt update; apt upgrade -y
```

* Install `nginx` web server
```
$ apt install nginx -y
```

### Run
``` 
$ nginx
```
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

__Nginx server__
```
$ nginx -s stop
```
