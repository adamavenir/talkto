talkto
======

Add a [SimpleWebRTC](http://simplewebrtc.com) video hangout to your site *just by forking this repo
and changing the CNAME.*

## Using talkto as a basic GitHub.io page

__Just fork this repo—and that's it.__
It should immediately work at __yourusername.github.io/talkto__

## Using talkto on your own domain name

- Change the CNAME to your own domain (or subdomain)

- At your DNS provider oint a __DNS CNAME record__ for your own domain to yourusername.github.io

- Wait for GitHub pages to show up. (It'll 404 for a bit before it recognizes your CNAME)

---

This simple thing uses [SimpleWebRTC](http://simplewebrtc.com) from [&yet](http://andyet.com).

This uses the SimpleWebRTC sandbox server for signaling. 

If you want to run your own signaling server, feel free to use the same code we're using for this (and Talky) which is at [github.com/andyet/signalmaster](https://github.com/andyet/signalmaster). (You'll also need to use your own version of SimpleWebRTC and configure the signaling server there.)
