Domarques pfSense theme
========

**Simple** customization of "the wall" theme. Some adjustments on styles, font size and interface width (fluid).

A 5 minute work, so, please, don't expect a perfect custom theme. I've done a quick check and most of pages are ok.

Maybe i'll change the UI icons using font awesome. 

The theme was made using pfSense 2.1.4-RELEASE. I can't determine, right now, if is compatible with previous versions.

Installation
--------

Download (git or zip) and upload files:

> /usr/local/www/themes/

    git clone https://github.com/domarques/pfsense-domarques-theme.git domarques

Then:

    scp -r domarques root@ip_or_fqdn_of_pfsense:/usr/local/www/themes/

Go to:

    http://ip_or_fqdn_of_pfsense/system.php

and set theme option.

Screenshot
--------
![Theme preview](preview.jpg "Theme preview")