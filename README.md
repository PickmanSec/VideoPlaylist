# VideoPlaylist
An auto playlist player to replace the part of PlugDJ I care about.

NOTES:
I am trying to not use any 3rd party resources such as jquery. 
This is html should be able to be run without webserver.
Internet is need to access youtube.
Playlists can be added to locastorage to avoid having to have files hosted or have them as seperate files.
Condense everything to be super minimal.


BUGS:
XSS All the things. Luckily no stored xss because of design.
Time sync is off by 20%ish. 1 second in real life is about 1.2 seconds in JS land. 
Playlist does not populate. WIP 
P2P sockets coming soon for chat integration. This is a dumb thing that should never exist but I want to explore this.




Example of usage at https://dropbox.pro
