# GriefBuddyPHP - GriefBuddy with Getgle Characteristics

I rewrote [k0rnh0li0's script](https://github.com/k0rnh0li0/GriefBuddy) in PHP that way anyone can run an instance of GriefBuddy on a crappy cpanel host.  You can easily get cpanel hosting for free or insanely cheap online. They are literally everywhere.  Just look up "free php cpanel hosting" and tons of results will come up.  

I host this on https://grief.getgle.org so feel free to use that if you don't want to host your own griefbuddyphp server

## requirements

All this script requires is PHP with the curl module enabled.

## how to set up on your own griefbuddyphp server

Make a Shodan account and get your API KEY

Unzip this repo onto your cPanel host

open "config.php" and put your Shodan API Key into where it says to put it

Create a new subdomain in cPanel, point the subdomain to the "public" folder

Set up a cron job through cpanel that runs "cron.php" every two minutes

That's it, you're done.  Get griefing, son!!!!!
