# docker

welcome to my docker compose file for server, it will save the config files and data to the /apps/docker folder so you can update without worrying about reconfiguring all the apps, you could mount or store your media in the /media folder so every docer can access it. The /mnt folder will be reserved to mount or store the torrent files incomplete and completed. Of course you could change this locations in the compose file. The cntainers included are: Sonarr (organizing and searching for tvshows), radarr (organizing and searching for movies), prowlarr (indexes searchers for linux ISO), Jellyfin (to organize and watch your media with HW transcoding), Flaresolverr (to solve cloudflare capcha), Protainer (a way to monitor and manage containers in a web interface), qBittorent (to torrent linux ISO), pihole (an adbloking DNS server with dns caching). 

## Ports used:
### - 8080,8118,9118,58946 qBittorrent proxy and web interface
### - 8081,53 pihole DNS
### - 8096,8920,1900,7359 Jellyfin web interface and discovery
### - 8191 Flaresolverr proxy port
### - 8989 Sonnar web interface
### - 7878 Radarr web interface
### - 9443 Portainer web interface
### - 9696 Prowlarr web interface
