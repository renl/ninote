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

Output from the read from db is shown below

> ==========================================
> 
> Note#1 @Mon Dec 31 19:05:35 +08 2018
> 
> First entry into my nifty note shell script
> This is a quick note taking tool for the command line
> 
> ==========================================
> 
> Note#2 @Mon Dec 31 19:07:38 +08 2018
> 
> Linux cmd: whois
> queries the whois database for information about public ip addresses
> 
> ==========================================
