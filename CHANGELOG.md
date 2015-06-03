[info] [Teamspeak] 2015-06-03 22:27:34 Updated to ver 3.0.11.2
[info] [Madsonic] 2015-06-03 22:10:24 Updated to ver 5.1.5200
[info] [SABnzbd] 2015-06-03 21:14:10 Updated to ver 0.7.20
[info] [SickRage] 2015-06-03 21:09:49 Updated to ver 4.0.23
[info] [Deluge] 2015-06-03 20:55:21 Updated to ver 1.3.11
[info] [Plex] 2015-06-03 20:43:44 Updated to ver 0.9.12.1.1079
[info] [Plex] 2015-06-03 20:35:45 Updated to ver 0.9.12.1.1079
[info] [NZBGet] 2015-06-03 20:10:15 Updated to ver 15.0
[info] [MiniDLNA] 2015-06-03 20:05:41 Updated to ver 1.1.4
[info] [Deluge] 2015-06-03 20:00:56 Updated to ver 1.3.11
[info] [Jenkins] 2015-06-03 19:54:54 Updated to ver 1.616
[info] [Jenkins] 2015-06-03 11:57:45 Updated to ver 1.616
[info] [Jenkins] 2015-06-03 09:22:49 Updated to ver 1.616
[info] [Jenkins] 2015-06-03 09:14:59 Updated to ver $(curl -s https://www.archlinux.org/packages/community/any/jenkins/ | grep -P -o -m 1 '(?<=<h2>)[^<]+' | grep -P -o -m 1 '[d.]+[^-]')
[info] [Jenkins] 2015-06-02 21:42:20 Updated to ver 1.616
[info] [Jenkins] 2015-06-02 16:21:30 Updated to ver 1.616
[info] [Jenkins] 2015-06-02 16:14:22 Updated to ver 1.616
[info] [Jenkins] 2015-06-02 14:56:39 Updated to ver 1.616
[info] [NZBGet] 2015/05/21 updated to version 15.0
[info] [SickRage] 2015/05/18 updated to version 4.0.21
[info] [SABnzbd] 2015/05/15 DelugeVPN] added in env variable to enable/disable vpn tunnel
[info] [SickRage] 2015/05/11 updated to version 4.0.20
[info] [Plex] 2015/05/05 updated to version 0.9.12.1
[info] [SickRage] 2015/05/05 updated to version 4.0.19
[info] [Plex] 2015/05/01 updated to version 0.9.12.0
[info] [SickRage] 2015/04/20 updated to version 4.0.17
[info] [SickRage] 2015/04/05 updated to version 4.0.15
[info] [MiniDLNA] 2015/03/30 tidy up dockerfile, now runs correctly as user nobody
[info] [Plex] 2015/03/30 updated to version 0.9.11.16
[info] [SickRage] 2015/03/30 updated to version 4.0.14
[info] [SickRage] 2015/03/23 updated to version 4.0.13
[info] [Sonarr] 2015/03/19 updated to version 2.0.0.3004
[info] [TeamSpeak] 2015/03/17 symlinked db to /config folder to allow safe update without loss of data
[info] [get_iplayer] 2015/03/16 added in schedule env variable to allow user to define schedule for restart of get_iplayer process
[info] [SickRage] 2015/03/16 updated to version 4.0.12
[info] [NZBGet] 2015/03/08 new docker image for release 14.2 plus inclusion of unzip and unrar
[info] [SickRage] 2015/03/08 new docker image for release 4.0.11
[info] [Sonarr] 2015/03/05 created a docker image of sonarr, this is also in the docker template repo so should now be visible
[info] [All] 2015/03/03 general tidy up, move commands in dockerfile to bash scripts, update base and ref new tag in dockerfiles for all apps
[info] [DelugeVPN] 2015/03/02 updated to 1.3.11 (release 3 for Arch Linux) which fixes issue with deluge webui api requests
[info] [MiniDLNA] 2015/02/26 updated to 1.1.4 (release 4 for Arch Linux)
[info] [DelugeVPN] 2015/02/26 allow ns lookup via eth0, this should then allow openvpn ping and ping-restart to work correctly
[info] [DelugeVPN] 2015/02/24 added in support for AirVPN
[info] [DelugeVPN] 2015/02/16 will now auto reconnect vpn tunnel on drop, allows user to define country to use as gateway, also included privoxy to bypass any filtering from isp of http/https traffic
[info] [DelugeVPN] 2015/02/12 now detects currently assigned local tunnel ip, and if changed then will re-configure incoming port for Deluge
[info] [DelugeVPN] 2015/02/10 now marked as orange - working but needs enhancements (automatic reconnect, [s]port forward checking[/s], end point selection)