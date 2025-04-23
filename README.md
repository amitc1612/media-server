# Media Server

Using docker compose, this repo sets up a media server running the following applications: 
- [Plex Media Server](https://hub.docker.com/r/linuxserver/plex): for streaming content remotely
- [qBitTorrent](https://hub.docker.com/r/linuxserver/qbittorrent): for downloading torrents
- [Radarr](https://hub.docker.com/r/linuxserver/radarr): for managing and downloading movies
- [Sonarr](https://hub.docker.com/r/linuxserver/sonarr): for managing and downloading tv series
- [Prowlarr](https://hub.docker.com/r/linuxserver/prowlarr): for managing indexers
- [Bazarr](https://hub.docker.com/r/linuxserver/bazarr): for managing and downloading subtitles
- [Overseerr](https://hub.docker.com/r/linuxserver/overseerr): for managing requests
- [Tautulli](https://hub.docker.com/r/linuxserver/tautulli): statistics for Plex Media Server
- [Heimdall](https://hub.docker.com/r/linuxserver/heimdall): Home page with links for each application

## Installation

1. install docker and docker compose 
```bash
yay -S docker docker-compose
```
2. create directories in your home folder
```bash
mkdir -p \
	$HOME/media/{backups,downloads,movies,temp,tv}
	$HOME/media_server/{bazarr,heimdall,overseerr,plex,prowlarr,qbittorrent,radarr,sonarr,tautulli}
```
3. TODO: continue readme

## Usage

```bash
plex up
```

## Contributing

Forks are welcome, but probably not any pull requests..

## License

[MIT](https://choosealicense.com/licenses/mit/)
