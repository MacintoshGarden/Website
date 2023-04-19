# GAIA
This is a system that is currently only tied to the discussion boards right now, and its purpose is to mirror images from external hosts.  
It is a solution to a couple of different issues.

**Solves certain issues, like ...**  
* Image is deleted due to inactivity at the host
* Image is deleted due to host being bought up or shut down
* HTTP/HTTPS confusion, some vintage browsers are unable to keep up with modern hosts
* Image format support on vintage browsers

## What GAIA does
When an offsite / external image is inserted into a post, GAIA will attempt to download the image and store it locally.  
The original download is archived and processed, creating different size copies and formats depending on browser compatibility.

The original URL is then rewritten to instead use the local copy. Depending on which theme is in use, it will attempt to select the appropriate image format as well.

GAIA will also attempt to automatically create the image tag required to inline the image, so that a user will only have to link the image itself and not have to worry about confusing tags - these can however be altered by the post owner after the initial post has been made.

Any images linked to our Image Hosting service will be (*at least should be*) ignored by GAIA initially, this may change further down the road.

## Image Formats
GAIA will generate a locally cached copy for each theme save for the Text-based version.

**JPG**  
This is the generally used image format for the default theme and is supported in all browsers.

**PNG**  
This image format is widely used within the Garden 2009 theme, users of this theme are expected to be using a newer browser with support for this format.

**WebP**  
Currently the only themes using this image format is the Modern theme as well as the Mobile theme, however if the browser is capable of displaying WebP images, these will be displayed regardless of theme in use.

## Bugs
There are some bugs I'm already aware of, I would however love to see reports if anyone comes across one (or more).
