gitPoweredSite
==============
An experiment to see if I can host a website on GIT.
The important files will be hosted on git.  

A subdomain called http://gitpoweredwebsite.co.nf will house some basic 
html5 that will call a file from this git repository.

that repository will fill it with contents on that page.

update 12-16-2013
=============
XMLhttpResquest appears to work if we are accessing a relative
site, but when it isn't it no longer has permission.

I am not sure how to get permission properly.

The error is "XMLHttpRequest cannot load <sourceURL>. Origin http://gitpoweredwebsite.co.nf is not allowed by Access-Control-Allow-Origin.";
