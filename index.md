# Homelab Setup Tutorial

# iRedMail 
- Installation
- Mail (Roundcube, Externe Programme)
- LDAP (LDAP als Identity Provider)
- Benutzerverwaltung (iRedAdmin)

# Docker
- Grundlagen
- Installation
- Docker 
- Netzwerke
- Container
- Volumes
- Images
- Docker Compose

# Reverse Proxy
- Grundlagen
- Reverse Proxy ohne GUI (Apache, NGINX, Traefik, Caddy)
- Reverse Proxy mit GUI (Nginx Proxy Manager, Zoraxy)
- Installation 
- Einrichtung

# Benutzerverwaltung und Single Sign-On
- Problematik und Grundlagen
- Lösungen

## Keycloak
- Installation
- Einrichtung
- User Federation (LDAP integration mit iRedMail)
- Einbindung von Clients via OpenID Connect
- Die Problematik mit nicht unterstützten Apps
- Lösungsansätze
## Oauth2 Proxy
- Installation
- Konfiguration von Oauth2 Proxy
- Konfiguration von Keycloak
- Hinzufügen von Apps via docker-compose.yml und config Dateien

# Vaultwarden Passwort und Passkey Manager
- Installation
- Einrichtung
- Konfiguration der Browsererweiterung
- Konfiguration der Mobile App 
- Einschränkungen und Lösungsansätze mit der Benutzerverwaltung

# Portainer (Docker Management über WebUI)
- Grundlagen
- Installation
- Einrichtung
- Tips&Tricks
- Integration mit LDAP und/oder OpenID Connect

# Nextcloud (Cloudspeicher und Mehr)
- Grundlagen
- Installation
- Einrichtung
- Apps
- Integration mit LDAP und/oder OpenID Connect

# VPN
- Grundlagen 
- VPN Server Softwares
- Installationsskripte
## Easy Wireguard (easy-wg)
- Installation
- Einrichtung
- Integration mit Oauth2 Proxy
## Pihole 
- Installation
- Einrichtung
- Integration mit Wireguard
- Integration mit Oauth2 Proxy

# Heimdall Dashboard
- Grundlagen
- Installation
- Einrichtung
- Integration mit Oauth2 Proxy
