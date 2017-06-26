### Déploiement d'un réseau Wifi
La portée du réseau Wifi émis par la Racebox est limité, il peut donc être nécessaire de déployer un réseau Wifi sur l'ensemble du site de compétition.
Pour celà, il suffit de :
- Connecter la Racebox à un Switch par son port Ethernet
- Configurer les points d'accès Wifi (par exemple un Ubiquiti NanoStation) que l'on va utiliser en mode d'obtention d'adresse IP automatique par DHCP
- Configurer le réseau Wifi émis par les points d'accès (Nom du réseau et mot de passe)
- Connecter ces points d'accès Wifi au Switch sur lequel est branché Racebox.

Les points d'accès utiliseront le serveur DHCP de Racebox pour attribuer des adresses IP automatiquement aux terminaux qui s'y connecteront.