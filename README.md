ZenPacks.community.FreeRADIUS
=============================

Provides monitoring and graphing for FreeRADIUS statistics. Currently total Access, Authentication and Accounting metrics are graphed, as well as the rate per 5 minute polling interval for each.

You will want to edit $ZENHOME/ZenPacks/ZenPacks.community.FreeRADIUS/ZenPacks/community/FreeRADIUS/libexec/freeradius to reflect your environment. Change "radclient localhost:18120 status adminsecret" to the port and administrator secret for your FreeRADIUS status server. See http://wiki.freeradius.org/config/Status for more information.

A new Monitoring Template named "FreeRADIUS" will be created.

Requires SSH credentials setup to run the commands.