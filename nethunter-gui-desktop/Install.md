## Nethunter Gui Desktop

### Installation

>* Before running `nethunter gui desktop` you have to install [nethunter-rootless](../nethunter-rootless) and download [nethunter app store](https://store.nethunter.com/)     

>* Install `nethunter kex bvnc` from _nethunter app store_

![bnvc](https://i.ibb.co/XDLG27K/bvnc.jpg)

### Run

> Open your _termux_ and type

```
$ nh
```

> Set your kex passwd for `kex bvnc` on nethunter terminal

```
$ kex passwd
```

![passwd](https://i.ibb.co/kc6mxGH/passwd.jpg)

> Start `vncserver` on port `5901`

```
$ kex
```
![vncserver](https://i.ibb.co/X7tyBKS/vncserver.jpg)

> Open the kex bvnc application and settings like this
```
type ( basic vnc )

title ( anything )

vnc server ( localhost )

port ( 5901 )

vnc password ( your kex passwd ) *keep
```
> Then `connect` and _wait_

![bvnc](https://i.ibb.co/s234WtQ/bvnc.jpg)

> __Nethunter gui desktop__ is ready

![kali](https://i.ibb.co/MswyhmR/kali.jpg)

> Stopping _vncserver_

```
$ kex stop
```

![kexstop](https://i.ibb.co/KhwzRpF/kexstop.jpg)


