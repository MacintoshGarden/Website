# Archive Mirrors - Web (HTTP/HTTPS)
WIP

## Web Mirrors
There's a certain structure we'd like for these, it's not enforced but makes everything much easier for anyone involved.

**URL**  
We have a specific domain set up for mirror use, as seen below.

country-code#server.mac.gdn  
As an example, the first mirror in Sverige (Sweden) would receive sv1.mac.gdn.

## Setting Up
We can supply an NGiNX vhost config along with a download script written in PHP.  
There are commented variables available depending on how the mirror host would like to set things up.

The default config does not allow listing directories or direct access to files.
