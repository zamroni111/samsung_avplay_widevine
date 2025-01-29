Simple Samsung AVPlay Widevine Player.<br>
It's tested on Tizen 6.5 TV (2022 series).

Make sure the HTTP content-type response header of the MPD file is "application/dash+xml".<br>
"https://storage.googleapis.com/shaka-demo-assets/angel-one-widevine/dash.mpd" will fail due to mismatched content type.

Additional features:
1. Subtitle display using HTML table element
2. Playback button control:<br>
a. play/pause button<br>
b. up button: fast forward 2/4/8x<br>
c. down & middle button: set 1x playback<br>
d. left & right button: seek -/+ 10 seconds<br>
e. channel up & down button: subtitle switcher<br>
f. channel guide button: show/hide subtitle<br>
g. return button: proper stop, close then exit.
3. Status text display: current play position, video duration, playback speed, subtitle id.
