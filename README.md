A simple bash script that makes for the simple cron monitoring and restarting of the Minecraft server daemon

Source from http://minecraft.gamepedia.com/Tutorials/Server_startup_script
Made changes to suit my needs, now serves as a proper croncheck script
There will be bugs.  Fix them.  Send me a note about it if you like and
I'll include them.  I can be reached on reddit as /u/jbranscum or post an
issue on GitHub utoc/mcinit

Licensing here: https://github.com/utoc/Dont-be-a-Jerk
This is open source.  Give credit where it is due if you decide to modify
this script as I have done

Replace HOMEDIR, MCUSERNAME, MCSERVERDIR as needed.
Cron entry should look like so:
*/5 * * * * /home/HOMEDIR/scripts/mcinit croncheck
30 04 * * * /home/HOMEDIR/scripts/mcinit restart

You need screen, uuencode and mailx for this script in addition to standard bash tools (pgrep, etc)
I cannot provide support on this.  Use at your own risk.  You have been warned.

If you're unsure of yourself, see the following: http://youtu.be/nuHfVn_cfHU

Also, these are Java 8 settings to use 4/8 gig ram.  If you have Java 7, make changes!
