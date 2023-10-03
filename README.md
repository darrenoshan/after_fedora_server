# Post Fedora Server Installation Guide

If you search for "Fedora Server Installation Guide" here is the official document link.

https://docs.fedoraproject.org/en-US/fedora-server/installation/interactive-local/

This is a personal script to run after installing a fedora server edition.

This project could save you alot of time on post-fedora installation.
Fedora is one of the most popular Linux distributions. https://en.wikipedia.org/wiki/Fedora_Linux

run the following code in a terminal with root permission and wait for it to stop :
```
cd ~
git clone https://github.com/darrenoshan/fedora_server_post_install.git 
cd fedora_server_post_install/
sudo bash main.sh normal 
```

to read the live log, open another terminal/shell and run the following commands:
```
tail -F ~/fedora_server_post_install/logs/*

```
