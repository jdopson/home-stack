# home-stack
Docker compose stack of home containers
Create a .env file in the same directory as the docker-compose.yml
```
TORGUARD_USER=<USER>
TORGUARD_PASS=<PASS>
TIMEMACHINE_USER=<USER>
TIMEMACHINE_PASS=<PASS>
HOME_HOSTNAME=<HOME_HOSTNAME>
LOCAL_NET=192.168.0.0/24
HOOBS_IP=192.168.0.34
PLEX_IP=192.168.0.35
LAN_INTERFACE=eth0
```
# docker compose up 
