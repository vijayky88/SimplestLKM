SimplestLKM
===========

"Hello World" Linux Kernel Module

Read our simple example messages in /var/log/messages

to install...

make

insmod hello.ko

tail -n 1 /var/log/messages

rmmod hello

tail -n 1 /var/log/messages
