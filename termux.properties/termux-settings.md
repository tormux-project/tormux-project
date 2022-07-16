## Termux Properties

### Installation

* `Wget` ( commandline tool for retrieving files using HTTP, HTTPS and FTP )
```
$ apt install wget
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

* Retrieving ``termux.properties`` file
```
wget https://raw.githubusercontent.com/tormux-project/tormux-project/main/termux.properties/config/termux.properties
```
