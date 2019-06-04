# extra UFW (uncomplicated firewall) application profiles

Copy the contents of applications.d in this repository to: `/etc/ufw/applications.d`

To see the new definitions run:

    sudo ufw app list
 
This repository provides application profiles (port numbers and protocol e.g. TCP or UDP) for:

 * AIM
 * Alertmanager
 * Apache
 * Bind9
 * Bonjour
 * Cache
 * CIFS
 * CUPS
 * Deluge
 * dhcp
 * dhcp6
 * distcc
 * DNS
 * Dovecot
 * Dropbox
 * elasticsearch
 * grafana
 * HTTP
 * HTTPS
 * identd
 * IMAP
 * IMAPS
 * Kerberos
 * kibana
 * KTorrent
 * L2TP
 * LDAP
 * LDAPS
 * logstash
 * LPD
 * Megasync
 * MongoDB
 * mosh
 * MSN
 * MySQL
 * NFS
 * Nginx
 * NTP
 * OpenSSH
 * OpenVPN
 * OSSEC
 * PeopleNearby
 * Polipo
 * POP3
 * POP3S
 * PostgreSQL
 * PPTP
 * Privoxy
 * Prometheus
 * prometheus-blackbox-exporter
 * prometheus-node-exporter
 * Proxy
 * qBittorrent
 * RDP
 * redis
 * Samba
 * SIP
 * SMTP
 * SNMP
 * Socks
 * spamd
 * SSH
 * SSL
 * submission
 * svnserve
 * Synergy
 * syslog
 * Telnet
 * TFP
 * Tor
 * Transmission
 * VNC
 * whois
 * WWW
 * XMPP
 * Yahoo
