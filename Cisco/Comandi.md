# Cisco

## Router
###### Base
**configure terminal**: entrare in modalità configurazione

**sh running-config**: visualizzare la configurazione attuale
###### Config
**interface fastethernet** *1/0.1*: entrare in modalità configurazione interfaccia
###### Config-If
**encapsulation dot1q** *vlanid*: associa la sottorete ad una vlan

**ip address** *IP* *NetMask*: associa un ip alla sottorete

**ip helper-address** *DHCP-IP*: associa la sottorete ad un server DHCP
## DHCP
###### Gateway
Il Gateway deve essere uguale all'IP della **sottorete**