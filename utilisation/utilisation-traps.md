### Utilisation des TRAPS
Racebox est compatible avec le [système TRAPS](http://www.traps-ck.com/doku.php) développé par Frédéri Mahieu, qui permet la transmission des pénalités depuis des terminaux Android par Wifi et par SMS.

Nous ne traiterons ici que le cas d'un réseau Wifi. Il faut réaliser les manipulations suivantes :
- [Déployer un réseau Wifi](./reseau-wifi) avec une couverture suffisante pour tous les postes de juge.
- Installer Traps Manager (disponible au téléchargement depuis [l'interface](./interface) de Racebox) sur un poste, **impérativement connecté à un Switch relié à Racebox.**
- Faire un export PCE depuis FFCanoe de la course à gérer.
- Lancer Traps Manager, sélectionner le mode Wifi.
- Si la sélection d'une adresse est requise, sélectionner l'adresse commençant par 192.168.25.
- Importer la liste des dossards : menu Dossards, Charger fichier FFCanoe, Remplacer la liste courante, sélectionner le fichier PCE précédemment exporté.
- Sur la partie basse de Traps Manager, sélectionner l'option "Addresse IP de FFCanoe", et rentrer l'adresse 192.168.25.1. Sélectionner "Faire suivre les pénalités", puis cliquer sur Connecter. **Traps Manager est maintenant prêt à recevoir les pénalités des terminaux et à les transmettre à FFCanoe**.

Pour chaque terminal Android :
- [Installer l'application Android Traps](http://www.traps-ck.com/doku.php?id=install-android)
- Se connecter au réseau Wifi déployé
- Lancer l'application
- Dans le menu, cliquer sur "Charger liste dossards", puis "Pénalités". Selectionner "Envoyer les pénalités", "par Wifi à TRAPSManager" avec détection automatique.
- Les terminaux sont maintenant prêt à transmettre les pénalités à Traps Manager.