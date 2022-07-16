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

### Handling Extra Keys

Ctrl+A  Move cursor to the beginning of line

Ctrl+C  Abort (send SIGINT to) current process

Ctrl+D  Logout of a terminal session

Ctrl+E  Move cursor to the end of line

Ctrl+K  Delete from cursor to the end of line

Ctrl+U  Delete from cursor to the beginning of line

Ctrl+L  Clear the terminal

Ctrl+Z  Suspend (send SIGTSTP to) current process

Ctrl+W  Clear prompt before word (a word is a set of characters after a space)


