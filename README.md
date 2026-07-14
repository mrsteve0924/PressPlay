
Shell script to generate a randomized playlist from local audio collection.        

Uses `cvlc` command to play audio files, but can really use any command line audio player.   
 
Quickly start listening to locally stored music without having to open up a media player gui or type a string of commands in the terminal. Map the `play` script to a keyboard shortcut for quick launching.  I also use `wstroke` which is a mouse gesture program for wlroots compositors.   

Optionally, configure `vlc` to run an HTTP server on localhost that provides a web-based interface for controlling playback and viewing the playlist. 
 
From Terminal   
`play` will queue up your locally stored audio files and play them randomly.   
`play-` will allow you to choose a specific artist or song   
`playstop` will stop the current running media player



