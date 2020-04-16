# Homelab ver. Oasis
Personal home server running Linux Ubuntu 18.04.4 LTS headless

## Build Specifications

AMD A8-7650K 3.3 GHz Quad-Core Processor	

Asus A68HM-Plus Micro ATX FM2+ Motherboard	

Kingston 8 GB (2 x 4 GB) DDR3-1333 Memory	

Seagate Barracuda 500 GB 3.5" 7200RPM Internal Hard Drive		

Rosewill FBM-X2 MicroATX Mini Tower Case		

Rosewill RD-Z 400 W 80+ Certified ATX Power Supply

## Webserver
Node.js, Express
> I decided to try hosting my own version of my React Application on my home server. I learned quite a bit on what it takes to actaully run a webserver. The webserver is not tied to a Domain name due to my ISP only providing static public IP addresses to bussiness accounts and port 80 for http is blocked. I managed to still have it accessable by searching for the IP and Port (http://XX.XX.XXX.XX:Port).

## Minecraft Server
java -Xmx1024M -Xms1024M -jar minecraft_server.1.15.2.jar nogui

> Wanted to also create a dedicated Minecraft server for my friends and I to play on. This project taught me a lot about port security, patch maintainence, and scripting. In the end I decided I needed more knowledge of the subject and decided to start studying for a CompTIA Sec+ certification.

## Media Server
PLEX

> Home Media server using plex. Future upgrades include better specs so it can stream 4k videos.

## Future Ideas
  - Crypto miner
  - Web Crawler
