SpotiBox
========

Raspi-based box which allows to chose and listen your Spotify Playlists.

Prerequisite
===
- A Raspberry Pi
- 3 buttons 
- A 16x2 LCD display (HD44870)
- A working mopidy server

Installation
=== 
Once you've plugged everything together (wiring diagram will come later) :
- Put your SpotiBox python file in /home/your-user/SpotiBox. 
- Edit the lines with the mpc commandes
- Put the spotibox init file in /etc/init.d/spotibox.
- Execute update-rc.d spotibox defaults
- Reboot & Enjoy 


ToDo
===
I am not a software developer, so I know a lot is missing. If someone is willing to help me, please do ;-) 
- Create the wiring diagram 
- Put a parameter for the mpc command 
