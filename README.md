Here are some chirp tools for use with OSG Connect.

The 'chirpd' init script will grab a list of authorized users, su to them, and run chirp_server at port=`id -u`, reporting to a 
catalog server at stash.osgconnect.net. This file should be placed in /etc/init.d 
