## Postgresql Termux

### Installation

```
$ apt install postgresql
```

### Skeleton Database

```
mkdir -p $PREFIX/var/lib/postgresql
```
```
initdb $PREFIX/var/lib/postgresql
```

### Run

* `Starting` the `database`
```
pg_ctl -D $PREFIX/var/lib/postgresql start
```

* `Stopping` the `database`
```
pg_ctl -D $PREFIX/var/lib/postgresql stop
```



