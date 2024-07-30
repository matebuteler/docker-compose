# docker-compose
A single docker-compose for all of my selfhosted services. This repo includes:

# Content:

- Radarr, to search for legal linux isos (and movies)
- Lidarr, to search for legal linux isos (and music)
- Sonarr, to search for legal linux isos (and TV)
- Readarr, to search for legal linux isos (and books) 
- Prowlarr, to search & index legal linux isos
- FlareSolverr, so that Prowalrr can bypass CloudFlare protection
- Jellyseerr, to manage request from Jellyfin to the arr's
- Jellyfin, to watch legal linux isos
- qBittorrent, to torrent legal linux isos

# Utilities:

- Nextcloud 
- Vaultwarden
- PufferPanel
- Homarr
- Frigate

# Network/Security:

- Adguard
- Traefik
- Authentik
- Suricata IDS (WIP)
- Uptime-Kuma

# Default Ports
Content:

 Lidarr: 455 - 
 Radarr: 54 -
 Sonarr: 453 -
 Readarr: 452 -
 Prowlarr: 451 -
 Flaresolverr: 8191 -
 Jellyseerr: 450 -
 Jellyfin: 449 -
 qBittorrent: 448 -

 Utilities:

 Nextcloud: 447 -
 Vaultwarden: 446 -
 PufferPanel: 445, 5657, 27015, 25565 -
 Homarr: 7575 -
 Frigate: 5000, 8554, 8555 - 

 Network/Security:

 Adguard: 444, 3000, 53, 67, 853 -
 Traefik: 443 -
 Authentik: 8000, 8443 -
 Suricata IDS (WIP) -
 Uptime-Kuma: 3001 -
