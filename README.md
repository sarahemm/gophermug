GopherMug
=========
SmugMug Gopher mole interface

Allows viewing categories/albums/images from your SmugMug library via a gopher
server supporting moles/CGI.

Example: gopher://sen.cx/1/cgi-bin/gophermug

Setup
-----
0. Change CFG_PATH in both 'authorize' and 'gophermug' to point to a config file
not within your gopher path.
0. Copy config.yaml to this location and edit it, inserting your SmugMug API key
and secret.
0. Run 'authorize' and follow the instructions. This will OAuth authorize the app
and add the new token into the config file.
0. Copy 'gophermug' into your gopher CGI directory.
0. Browse to wherever you put the gophermug file!

Bugs
----
Very likely!
