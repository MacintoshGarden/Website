# Archive Mirrors
This is generally for anyone who wishes to assist in providing access to our archive by providing storage space and bandwidth.

## Requirements
We're looking at long-term availability when it comes to archive mirrors, something that goes down after a few months or a year is of zero interest to us.  
Thinking twice before committing is a base requirement.

# Web Mirrors
There's a certain structure we'd like for these, it's not enforced but makes everything much easier for anyone involved.

**URL**  
We have a specific domain set up for mirror use (mac.gdn), as seen below.

*country-code#server*.mac.gdn  
As an example, the first mirror in Sverige (Sweden) would receive sv1.mac.gdn, a third mirror in Finland would receive fi3.mac.gdn etc.

## Synchronising
Mirror hosts have access to the rsync server, or special FTP access in case rsync isn't an option.

The *incoming* folder is excluded in both.

## Serving
We can supply an NGiNX vhost config along with SSL certificates if HTTPS is going to be used, and a download script written in PHP.  
There are commented variables available depending on how the mirror host would like to set things up.

The default config does not allow listing directories or direct access to files.

# FTP Mirrors
Probably the easiest to host and maintain, since the base requirement is a means to synchronise files at regular intervals and provide access via FTP.