---
title: 'Setting Up Statrix On Grav'
published: true
date: '05-01-2016 11:36'
process:
    markdown: true
    twig: false
routable: true
cache_enable: true
visible: true
header_image: '1'
summary:
    enabled: '1'
    format: short
child_type: default
taxonomy:
    tag:
        - grav
        - digitalocean
    category:
        - blog
        - software
---

**To HTTPS Or Not To HTTPS?**

===

If you are actually reading this blog you might have noticed that my IP address changed. Indeed, if you somehow bookmarked my IP rather than the name you aren't reading this. I've ended up switching the VPS underneath this site because...

I completely messed things up!

Thank goodness for Git and [GitHub!](http://github.com)

Originally this site was simply going to be a replacement for [Statrix](http://statrix.com). It's turning into something else altogether. Which is to say, it's pretty much the same only different.

As I started to explain in another post this site is being built on [Grav](https://getgrav.org) rather than [Wordpress](https://wordpress.org). Don't get me wrong, there's no problem with Wordpress, it's mostly I felt like trying something else. Grav is a flat file CMS not a DB driven site and thus qualifies as something different.

I've also gone off to [DigitalOcean](https://www.digitalocean.com) as my host. Instead of shared hosting this site has it's own [VPS](https://en.wikipedia.org/wiki/Virtual_private_server) or Virtual Private Server. Of course that's running on shared hardware, but hey, I'm not starting my own server farm.

I'd originally set this up using [ServerPilot](https://serverpilot.io) as front end to take care of updating, patching, security, and so forth. Well it does a great job, but you know...I sort of like all that stuff and since I didn't know quite what is was actually doing (free account is somewhat limited as you'd expect) it seemed to me I should run this myself and learn the nuts and bolts before I turn it over to an automaton.

I'd actually been able to get everything running just as I wanted it when I started messing around and, yep, broke it. Since I wanted to run it myself it seemed like a good time, while there were few posts, to start over 'manually.' Hence the new IP.

I also decided I had to use HTTPS and, preferring not to pay, am using [Lets Encrypt](http://letsencrypt.org). It's [Linux Foundation ](https://collabprojects.linuxfoundation.org) Collaborative Project which is great. And, sure enough, it works, it's free, and really, when you boil it down, it's easy.

So here I am again. This time I think I'll be able to stay up and running for a while. Check out the tech sites I'm using and I think you'll be impressed - I am.

Aloha!
