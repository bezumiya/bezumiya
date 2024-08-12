
```
root@b-01:~# insmod main.ko
root@b-01:~# dmesg

[    0.000000] bezumiya: rootkit successfully loaded
[    0.000000] bezumiya:          /\___/\
[    0.000000] bezumiya:          \ -.- /
[    0.000000] bezumiya:          `-.^.-'
[    0.000000] bezumiya:            /"\

root@b-01:~# dmesg -c
root@b-01:~# echo "wh0ami" > /dev/null; dmesg
[    0.000000] bezumiya: Hi, I'm bezumiya
[    0.000000] bezumiya: here's a place where I'll post codes involving my blog posts
[    0.000000] bezumiya: or codes that I'm currently developing.

root@b-01:~# dmesg -c
root@b-01:~# echo "Skill$" > /dev/null; dmesg
[    0.000000] bezumiya: [Linux] [Bash] [Golang]
[    0.000000] bezumiya: [Privacy] [RedTeam] [Network Pentest]

root@b-01:~# dmesg -c
root@b-01:~# echo "c0ntact" > /dev/null; dmesg
[    0.000000] bezumiya: [Email]:   bezumiya@riseup.net
[    0.000000] bezumiya: [discord]: bezumiya
[    0.000000] bezumiya: [xmpp]:    bezumiya@exploit.im

root@b-01:~# dmesg -c
root@b-01:~# rmmod bezumiya
!! Nice Try !!

Connection to ***.***.***.*** closed.
```

---
