# Clipwrite

Clipwrite is a simple hacky script that periodically takes input from the
system clipboard and appends that to a file given as an argument.

It depends on xclip

# Youtube-clip

Youtube-clip uses clipwrite and youtube-dl to let users quickly create a list
of videos to download.

Run youtube-clip then copy links to videos into the system clipboard; these get
appended to a list of urls. End the clipboard-reading phase by copying the text
`end` (hacky, I know). Then youtube-dl will fetch all the urls which were
copied by the user.
