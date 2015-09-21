vagrant-docker-debian-latest
======================

This is a fork of a very basic docker/vagrant config to use debian-latest.

Installation
------------

Install vagrant: using http://vagrantup.com/downloads.html

If you are using linux, install docker: http://docs.docker.com/linux/step_one/
On mac and windows, install docker toolbox: https://www.docker.com/toolbox

Clone this repo

From repo folder:

    vagrant up

    # on mac and windows, you will be asked for a password, enter: tcuser
    # you will be asked for password twice for 2 folders to sync

    vagrant ssh  # user tcuser password again

    # enjoy your docker 'virtual' machine!
