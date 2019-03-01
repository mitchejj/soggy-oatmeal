---
title: "On the other side of infinity"
date: 2018-12-29T04:58:15Z
draft: true
---
I wanted to title this "About: static flux?", I was going to write a 'Hello World' post, before decipher that deception for what it represents.

Every about page I've written seems to dive into the countless sites I've had in the past... I rater not go to deep into that so I will just say I've had staticly generated website now for sometime. I love many aspects of static site generation from the lack of databases, the ability to track/see changes a post/page, to being able deploy anywhere. A static build system also lets me tinker with something until I'm able to generate something that, well... something that satisfy that self-indulgent desire to feel special.

That same self-indulgent desire lead me to wanting to buy a Raspberry Pi and build something with it... maybe build a NAS or run a personal git server, or even a VPN. Yet the hardware being what it is was a bit to slow for my taste. That quickly turned into trying cluster of Pi's so I bought a few Rasperry Pi's and tinkered away. As I became more consumed with the project the more I realize the Pi's where not what I really wanted.

Eventually I landed on vultr, and a $2.5o/month micro-cloud instance. For that I wouldn't have to wory about simple things like Pi not getting enough power or SD card corruption. I also gave me fast network and disk I/O. I chose to give Fedora a try and eh... it wasn't want I wanted but I kept the instance going... just sitting around burning up the the pre-paid credits and promo credits I had.

I've circled back on my vultr instance and my desire to do some self hosting. I don't know how but I stumbled accross traefik which is a clever peice of software that takes away many different headaches self hosting presents, but the big on to me is wildcard certificates with Let's Encrypt [ACME V2](https://community.letsencrypt.org/t/acme-v2-and-wildcard-certificate-support-is-live/55579). Now I know a rolling distro isn't the ideal choice for a server, I know so many 'things' can go wrong. However, I know I prefer Arch Linux over Fedora simply because I find that same contentment in running `pacman -Syu` as I find tinkering with a static build system.

One project I've been wanting to tackle for sometime is running my own git server, with a web presence; which is another topic all together. I knew I would face a few stumbling blocks so I wanted somthing up and running to help guide me in finding where my problem existed, somehow that lead me to running an instanace of Ghost. Now I have a problem as I realize all that idiosyncratic, self-indulgent, tinkering has prevent me communicating my thoughts and ideas.

With any luck I will be better at journaling "me" and my voyage
