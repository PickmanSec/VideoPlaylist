# VideoPlaylist
An auto playlist player to replace the part of PlugDJ I care about.<br/>
<br/>
https://plugapi4py-houdhakker2-2.c9.io/song is were some of the code was taken from.
NOTES:<br/>
I am trying to not use any 3rd party resources such as jquery. <br/>
This is html should be able to be run without webserver.<br/>
Internet is need to access youtube.<br/>
Playlists can be added to locastorage to avoid having to have files hosted or have them as seperate files.<br/>
Condense everything to be super minimal.<br/>
<br/>

BUGS:<br/>
XSS All the things. Luckily no stored xss because of design.<br/>
Time sync is off by 20%ish. 1 second in real life is about 1.2 seconds in JS land. <br/>
Playlist does not populate. WIP <br/>
P2P sockets coming soon for chat integration. This is a dumb thing that should never exist but I want to explore this.<br/>




Example of usage at https://dropbox.pro
