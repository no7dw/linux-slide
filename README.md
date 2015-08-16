linux intro
  #linux shell
  #linux cmd

system： price, open source software： safety, amount file： authority, attri Habit： interface, command support： tech, dev ... ...
------------------------------------------------------------------------

## install sofware ##
### install from ubuntu source ###
    apt-get update
    apt-cache search {package-name}
    apt-get install {package-name}
    apt-get remove/clean {package-name}

### install from source code ###

    #Name: software name-version-reversion-type
    Type: tar(.tar.gz/tar.gz2/..),
    tar -zxvf xxx.tar.gz 
    #bz2 (tar -jxvf) 
    ./configure
    make
    make install(make uninstall)
    make clean


 zip

    unzip package.zip

rpm(.rpm)

    rpm -i package.rpm

dpkg(.deb)

    dkpg -i package.deb

# useful command line #

## for log file ##

    vim / vi, cat
    head, tail
     more, less
     grep
     awk, sed

## help ##
don’t know how to

    command -h 
    command --help
    david@Wade:~$ man crontab
    ( Linux Programmer's Manual)
    david@Wade:~$ man 3 printf 

## Directory and it’s meaning ##

    ls /

[linux directory intro][1]


## fast vim intro ##

> find -- /
go to line-54   --- enter: 54; enter: G
up down left right --- hjkl
delete --- enter: dd; delete mul line , enter: number to delete , enter :dd
write :enter: i / a
save: enter: esc, w
quit: enter: esc, q
...

## user and auth ##

    ls -l /

> drwxrwxr-x+ 58 root     admin  1972 Aug 16 10:30 Applications
drwxr-xr-x+ 62 root     wheel  2108 Jul  5 22:50 Library
drwxr-xr-x@  2 root     wheel    68 Sep 10  2014 Network

### permission ###

> user  user-group  others
drw   xr-  xr-x

**try not to use sudo , unless you had to**




  [1]: http://www.cnblogs.com/no7dw/archive/2013/02/18/2915840.html
