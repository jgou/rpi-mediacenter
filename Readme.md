h1. rpi-mediacenter

Docker Compose to start a mediacenter in your Rasberry Pi

h2. Description

By running the compose file, you will start Docker containers for the following services:
# Samba Server
# Plex Server
# RTorrent Torrent Client
# Transmission Torrent Client

h2. Configure and start

Modify samba.env and transmission.env to setup the users and passwords to be used by Samba and Transmission
Once you establish these values, run the compose file

```
docker-compose up
```

h2. References

pms-docker folder is the content of official Plex Media Server Docker repository (https://github.com/plexinc/pms-docker)
