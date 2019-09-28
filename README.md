# thursa
## readme.doc for thursa - last updated 28 Sep 2019

This is a companion script which provides a basic interface and UX for NRSC5. It can also process
audio by piping it to mpv.

Prerequisites:
To use it you'll need to install NRSC5: https://github.com/theori-io/nrsc5
and mpv: https://github.com/mpv-player/mpv

Install:
Once you have these going, clone/copy the thursa script.

Operate:
Run the thursa script and follow the prompts. You enter an HDradio station by frequency and then
opt to process the audio with mpv or not.

^c to exit while playing

Troubleshooting:
If thursa errors out, check that both nrsc5 and mpv can run.
This is tested working with nrsc5 v1.0 and mpv v 0.29.0 on macOS 10.14.6 (with supplemental update 2), a fully up-to-date homebrew-based install of gnuradio, and a fully up-to-date install of homebrew itself. 
