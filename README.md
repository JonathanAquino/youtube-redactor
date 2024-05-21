# youtube-redactor
A tool for redacting parts of a YouTube video.

This tool lets you remove selected scenes from a Youtube video by specifying start and end times in seconds.

For example,

http://jonathanaquino.com/youtube-redactor/redact.html?embedId=dQw4w9WgXcQ&redact=44-60,86-119,162-208

redacts the choruses from Rick Astley's Never Gonna Give You Up. dQw4w9WgXcQ is the ID of the video, and 44-60,86-119,162-208 are the time ranges to remove (in seconds). 

## Why doesn't the link work with purchased content?

I'm not sure why the above link gives "An error occurred" with purchased content.

http://jonathanaquino.com/youtube-redactor/redact.html?embedId=OQuTiDMC9Zo&redact=10-20

It does work if you save the file locally.

file:///Users/jonaquino/projects/youtube-redactor/redact.html?embedId=OQuTiDMC9Zo&redact=10-20
