Config for my ongoing OLaaS (Old Laptop as a Server) project.

Current configured services:
- [Jellyfin](https://jellyfin.org/)
- [Navidrome](https://www.navidrome.org/)
- [Immich](https://immich.app/)
- [Qbittorrent](https://qbittorrent.org/)
- [TSDProxy](https://github.com/almeidapaulopt/tsdproxy)

Services can be accesed outside of LAN by using Tailscale, reverse proxy configured with TSDProxy. This is configured on the docker-compose-complete.yml

For the moment, Im not using all the services, only Jellyfin, ultil I get new storage for the machine this config runs on. The current docker-compose.yml is provitional.

The laptop is also running the following software but without docker *yet*:
- [Syncthing](https://syncthing.net/)
- [Cockpit](https://cockpit-project.org/)

