Ispconfig Apache config for Debian / Ubuntu
===========================================

![Logo](https://raw.githubusercontent.com/VitexSoftware/ispconfig-apache/master/ispconfig-apache.png "logo")

Debian package allowing apache use ispconfig's *.vhost config files.

Building package
----------------

    apt-get -y install devscripts dpkg-dev
    git clone git@github.com:VitexSoftware/ispconfig-apache.git
    debuild -i -us -uc -b


Installation
------------

You can use repo:

    wget -O - http://v.s.cz/info@vitexsoftware.cz.gpg.key|sudo apt-key add -
    echo deb http://v.s.cz/ stable main > /etc/apt/sources.list.d/vitexsoftware.list
    apt update
    apt install ispconfig-apache

