Simple Samsung AVPlay Widevine Player.<br>
It works in Tizen 6.5 TV.<br>
Make sure the HTTP content-type response header of the MPD file is "application/dash+xml".<br>
"https://storage.googleapis.com/shaka-demo-assets/angel-one-widevine/dash.mpd" will fail due to mismatched content type.

Additional features:
1. Subtitle display using HTML table element
2. Playback button control:
a. play/pause button
b. up button: fast forward 2/4/8x
c. down & middle button: set 1x playback
d. left & right button: seek -/+ 10 seconds
e. channel up & down button: subtitle switcher
f. return button: proper stop, close then exit.
