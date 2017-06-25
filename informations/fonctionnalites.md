### Fonctionnalités existantes
Racebox est un serveur Linux pré-configuré qui prend en charge les aspects de base suivants, indispensables au bon fonctionnement d'un réseau informatique de course :

* Mise en réseau (serveur DHCP et point d'accès Wifi)
* Base de données (serveur MySQL pour FFCanoe et le futur Compet'FFCK)

**Racebox remplace donc Wamp** mais propose également des fonctionnalités supplémentaires :

* Serveur FFCanoe : Tous les postes FFCanoe ont la même configuration, pas besoin de modifier le paramétrage du réseau, le serveur FFCanoe tourne sur Racebox.
* Commmunication : serveur de VOIP qui permet une communication vocale sans fil entre différents postes (ordinateurs, smartphone ou tablette), par exemple entre le départ et l'arrivée, sous réserve d'une couverture Wifi suffisante

### Fonctionnalités à venir
De nombreuses améliorations et fonctionnalités sont prévues, dans l'ordre des priorités :
* Résultats en ligne (à venir très prochainement)
* ...

### Spécifications techniques
La Racebox se base sur une carte Raspberry Pi 3, équipée d'un système d'alimentation avec batterie.
- Processeur quad-core 1,2 GHz
- Mémoire vive 1Go
- Port ethernet 10/100
- Wifi 802.11n (2 interfaces)
- Carte micro-SD 16 Go
- Autonomie en cas de coupure de courant : environ 15 min
- Alimentation 5V 3.0 A