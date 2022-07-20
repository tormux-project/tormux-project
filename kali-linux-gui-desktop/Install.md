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





