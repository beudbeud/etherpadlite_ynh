# Etherpad pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/etherpad.svg)](https://dash.yunohost.org/appci/app/etherpad) ![](https://ci-apps.yunohost.org/ci/badges/etherpad.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/etherpad.maintain.svg)  
[![Installer Etherpad avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=etherpad)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Etherpad rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Etherpad est un éditeur collaboratif en temps réel évolutif pour des milliers d'utilisateurs simultanés en temps réel. Il fournit des capacités complètes d'exportation de données et s'exécute sur votre serveur, sous votre contrôle. 

**Version incluse :** 1.8.14~ynh1

**Démo :** https://video.etherpad.com/

## Captures d'écran

![](./doc/screenshots/etherpad.gif)

## Avertissements / informations importantes

## Configuration

Vous pouvez accéder au panneau d'administration d'Etherpad à l'adresse `domain.tld/admin`. Le fichier de configuration d'Etherpad est `/var/www/etherpad/settings.json`.

*Skin Builder* (accessible à l'adresse `domain.tld/pad/p/test#skinvariantsbuilder`) vous permet de personnaliser l'apparence de votre pad. Il vous donnera un paramètre à copier dans votre fichier de configuration `/var/www/etherpad/settings.json`.

## Documentations et ressources

* Site officiel de l'app : https://etherpad.org/
* Documentation officielle de l'admin : http://etherpad.org/doc/v1.8.14
* Dépôt de code officiel de l'app : https://github.com/ether/etherpad-lite
* Documentation YunoHost pour cette app : https://yunohost.org/app_etherpad
* Signaler un bug : https://github.com/YunoHost-Apps/etherpad_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/etherpad_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/etherpad_ynh/tree/testing --debug
ou
sudo yunohost app upgrade etherpad -u https://github.com/YunoHost-Apps/etherpad_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps