rpi-logs
========

Raspberry Pi Configuration &amp; Tweaking Logs

This repository is the result of my very first experience having hosed a Raspberry Pi configuration...  I performed a sequence of changes out of order, and found myself completely locked out of my own system.  As I re-imaged my SD Card, I lamented my lost configuration (so far just getting my Bluetooth Keyboard / Mouse combo working as desired) and realized I should maintain logs as to how I got various things working.  As I've recently fallen head-over-heels in love with GIT, I took the only logical path: this repository.


Raspbian
========

My Raspian load is meant to fulfill my needs for a general Linux server: File Server (and Media Server), SSH Host for when I need a CLI fix from my Windows gaming box, and Development Host for any project that catches my fancy.

I start by imaging an SD Card with the latest Raspbian image (currently Wheezy).  When raspi-config opens up, I expand the filesystem to use the entire card.  Then I customize my keyboard to be English (US), change the password, set my locale, and update the timezone.  Most importantly, I enable the SSH server, as I desperately want that capability, and I configure it to boot straight into X for convenience.  Then I finish, and allow a reboot.  Once I get my desktop, I start a terminal and clone this repository.
