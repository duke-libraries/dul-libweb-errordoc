# dul-libweb-errordoc
Static Files used on libweb to present static pages as error documents served by Apache web server.

## Current Files
* `server_error` - contains the copy served to patrons and staff when a Server Error is encountered.
* `site-maintenance` - contains the copy served to patrons and staff when ITS is performing maintenance.

## Current Deployment
These files are currently deployed on two servers within the DUL VM space:

* `/var/www/dukeweb/PerkinsLibrary/htdocs/error` on __libweb-01__.
Note that you will have to switch to the 'cmslib' user, using `su -u cmslib -i`, before pulling files.

* `/srv/web/error` on __libcms-01__



