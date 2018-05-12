Evolve https://www.evolvehq.com/welcome
Tunngle https://www.tunngle.net/en/
Gameranger https://www.gameranger.com
LAN Bridger http://www.lanbridger.com/
Hamachi https://www.vpn.net/

ZeroTier! https://www.zerotier.com/download.shtml
* Free for 100 devices
* No port forwarding

Here's how you'd set it up:
* Host person creates a my.zerotier.com account and creates a Network there (Check the IPv4 Auto-Assign box)
* Host person gives the Network ID to everyone else
* Everyone installs ZeroTierOne
* Everyone tells ZeroTierOne to join Network ID
* Host person clicks Auth on everyone's device at my.zerotier.com
* Now everyone is on the same LAN :)


#ZeroTier #VPN
1. curl -s 'https://pgp.mit.edu/pks/lookup?op=get&search=0x1657198823E52A61' | gpg --import && \
if z=$(curl -s 'https://install.zerotier.com/' | gpg); then echo "$z" | sudo bash; fi
2. sudo zerotier-cli join c7c8172af1b06f66
3. #Goto https://my.zerotier.com/network/c7c8172af1b06f66 andf allow Auth to new client

https://my.zerotier.com/network/c7c8172af1b06f66
https://paperspace.zendesk.com/hc/en-us/articles/115004997928-How-to-Create-a-VPN-tunnel-with-ZeroTier-Windows-



#Hamachi  #VPN
wget https://www.vpn.net/installers/logmein-hamachi_2.1.0.174-1_amd64.deb ; echo $?
sudo dpkg -i logmein-hamachi_2.1.0.174-1_amd64.deb ; echo $?
sudo hamachi login  ; echo $?
sudo hamachi do-join "386-065-597" ; echo $?
https://secure.logmein.com/central/Central.aspx
