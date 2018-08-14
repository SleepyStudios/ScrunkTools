# Scrunk Tools
A collection of scripts to automate Scrunk server setup/maintenance 

## Server Parameters
You can add on parameters to customise your server e.g. 'java -jar ScrunkServer.jar -n Scrunkland --map freeforall --tcp 4998 --udp 4999':

* -n or --name: Overrides the <name> config variable. Useful when mass-launching servers

* -m or --map: Filename of the map you want to use (found in the maps folder). No need to include the extension

* --tcp: TCP port to use (default 5000)

* --udp: UDP port to use (default 5001)

* -h or --hidden: Your server won't come up in the server browser or in matchmaking
