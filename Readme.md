# From [Platform Tools Installation][pti-sharepoint]:

Download and install [memcached][memcached]. Or you can create a docker-compose.yml file with the following to run it locally in docker. Once you have that file created you can run the following commend in the same directory: `docker-compose up -d`. That should make it available at localhost:11211.
1. memcached: image: sylvainlasnier/memcached ports: - "11211:11211" command: sudo -u memcache /usr/bin/memcached -vv

[memcached]: https://memcached.org/
[pti-sharepoint]: https://lampogroup.sharepoint.com/tech/DigitalProductManagement/EveryDollarDigitalManagement/SitePages/Engineering/Platform%20Tools%20Installation.aspx
