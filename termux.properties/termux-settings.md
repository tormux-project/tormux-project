## Termux Properties

### Installation

* `Wget` ( commandline tool for retrieving files using _HTTP_, _HTTPS_ and _FTP_ )
```
$ apt install wget -y
```

### Setup

* If the `termux.properties` file is not found then go to the next step

```
rm .termux/termux.properties
```

* If the `.termux` folder doesn't exist then create the folder first

```
mkdir .termux
```

* Retrieving ``termux.properties`` file to folder `.termux`
```
wget https://raw.githubusercontent.com/tormux-project/tormux-project/main/termux.properties/config/termux.properties -P .termux
```

### Reload Settings
```
termux-reload-settings
```

### Handling Terminal Sessions

__CTRL+T__ Create session terminal

__CTRL+N__ Rename session terminal

__CTRL+1__ Previous session terminal

__CRTL+2__ Next session terminal



### Handling Extra Keys

__Ctrl+A__  Move cursor to the beginning of line

__Ctrl+C__  Abort (send SIGINT to) current process

__Ctrl+D__  Logout of a terminal session

__Ctrl+E__  Move cursor to the end of line

__Ctrl+K__  Delete from cursor to the end of line

__Ctrl+U__  Delete from cursor to the beginning of line

__Ctrl+L__  Clear the terminal

__Ctrl+Z__  Suspend (send SIGTSTP to) current process

__Ctrl+W__  Clear prompt before word (a word is a set of characters after a space)


