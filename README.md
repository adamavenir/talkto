talkto
======

Add a [SimpleWebRTC](http://simplewebrtc.com) video hangout to your site *just by forking this repo
and changing the CNAME.*

## No, seriously:

__Step 1: Fork this repo__

__Step 2: Change the CNAME__

## Well, okay. 

So you *also* have to make sure a couple other little details are square.

Namely:

- Create a gh-pages branch to enable GitHub Pages for your repo.

- Point a CNAME record for your own domain to yourusername.github.io

---

This simple thing uses [SimpleWebRTC](http://simplewebrtc.com) from [&yet](http://andyet.com).

This uses the SimpleWebRTC sandbox server for signaling. 

If you want to run your own signaling server, feel free to use the same code we're using for this (and Talky) which is at [github.com/andyet/signalmaster](https://github.com/andyet/signalmaster). (You'll also need to use your own version of SimpleWebRTC and configure the signaling server there.)
