vlc_sync
========

Synchronize two VLC players over network.


Enable the D-Bus contol interface
---------------------------------

To use this you want to make sure that your version of VLC is connected to the D-Bus control interface. To do this, open the preferences window in VLC ("Tools" > "Preferences"), mark "All" under "Show settings" and navigate to "Control interfaces" under "Interface". Tick the "D-Bus control interface" box if there is one. If you are running later versions (like VLC 2.1.4), chances are that VLC is already connected to the D-Bus control interface and there is no box to tick - good  on you!


Run vlc_sync
------------

Make sure that the file is executable (`~$ chmod +x vlc_sync`) then, to run: `~$ vlc_sync [OPTION] TARGET_ADDRESS`

