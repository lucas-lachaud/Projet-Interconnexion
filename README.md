# Projet-Interconnexion


## Objectif 

Construire un AS et pouvoir le connecter aux AS des autres groupes. 


## Outils

- Docker : lance les routeurs et les services
- Kathará : crée les liens de la maquette
- FRRouting : gère OSPF dans notre AS et BGP avec les AS voisins
- Git : partage les configurations du groupe et permet le travail en simultaner

## Fonctions à mettre en place

### Dans notre AS

- Routage dynamique et interconnexion avec les autres AS
- Accès réseau pour une entreprise et des particuliers
- Connexion d’un particulier sans configuration manuelle
- Service DNS
- QoS pour le trafic des entreprises

### Pour notre entreprise

- DHCP et DNS d’entreprise
- Sécurité d’accès au réseau et gestion des utilisateurs
- VoIP et au moins un autre service applicatif à définir
- VPN entre le site principal et le site annexe
- Accès sécurisé d’un employé distant
