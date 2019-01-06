# ninote
sqlite based Note taking tool written in bash shell script

# Example

First time `nn` is run, an sqlite db will be created

``` bash
nn
```

Subsequent `nn` command will prompt user to write their message. The message will be timestamped 
and stored as a record in the db.

The following will read from the db

``` bash
nn read
```
