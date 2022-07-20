## Kali Linux Gui Desktop

### Installation

* Before running `kali linux gui desktop` you have to install [nethunter-rootless](../nethunter-rootless) and download [vnc-viewer](https://play.google.com/store/apps/details?id=com.realvnc.viewer.android)  

```
$ nh
```
```
$ sudo apt install udisks2 xfce4 xfce4-whiskermenu-plugin qterminal dbus-x11 firefox-esr tigervnc-standalone-server kali-themes tightvncserver xfce4*
```

* Remove `udisks2.postinst` and echo with blank text
```
sudo rm /var/lib/dpkg/info/udisks2.postinst
```
```
echo "" >> /var/lib/dpkg/info/udisks2.postinst
```

* Configure ( _dpkg_ )
```
sudo dpkg --configure -a
```
```
apt-mark hold udisks2
```

* Remove _xstartup_ file and _adding bash script_ ( save it __CTRL+X Y ENTER__ )
```
rm .vnc/xstartup
```
```
nano .vnc/xstartup
```

![xstartup](https://i.ibb.co/8Y2RMD7/xstartup.jpg)

### Run

* Make a command in `/usr/bin/` to make it easier to run _vncserver_ ( save it __CTRL+X Y ENTER__ )
```
sudo nano /usr/bin/vncstart
```
```
vncserver -geometry 1920x920 -xstartup /usr/bin/xfce4-session
```
![vncstart](https://i.ibb.co/Cw4BcGc/vncstart.jpg)

