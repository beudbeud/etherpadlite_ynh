# Etherpad pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/etherpad.svg)](https://dash.yunohost.org/appci/app/etherpad) ![](https://ci-apps.yunohost.org/ci/badges/etherpad.status.svg) [![](https://ci-apps.yunohost.org/ci/badges/etherpad.maintain.svg)](https://github.com/YunoHost/Apps/#what-to-do-if-i-cant-maintain-my-app-anymore-)  
[![Installer Etherpad avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=etherpad)

*[Read this readme in english.](./README.md)*

> *Ce package vous permet d'installer Etherpad rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, merci de regarder [ici](https://yunohost.org/#/install_fr) pour savoir comment l'installer et en profiter.*

## Résumé
Etherpad est un éditeur en ligne Open Source hautement personnalisable qui permet l'édition collaborative en temps réel.  
Ce paquet installera les mêmes plugins que [Framapad](https://framapad.org/).

**Version embarquée :** 1.8.6

## Captures d'écran

![](https://github.com/ether/etherpad-lite/blob/develop/doc/images/etherpad_demo.gif)

## Démo

* [Démo officielle](https://video.etherpad.com/)

## Configuration

Vous pouvez accéder à deux panneaux d'administration différents, pour Etherpad en accédant à `domain.tld/admin` et pour MyPads par `domain.tld/mypads/?/admin`. Vous pouvez également trouver le fichier de configuration pour Etherpad à `/var/www/etherpad/settings.json`.

*Skin Builder* (accessible à cette adresse `domain.tld/pad/p/test#skinvariantsbuilder`) vous permet de personnaliser l'apparence de votre pad. Il vous donnera un paramètre à copier dans votre fichier de configuration `/var/www/etherpad/settings.json`.

## Documentation

 * Documentation officielle : http://etherpad.org/doc/v1.8.6
 * Documentation YunoHost : https://yunohost.org/#/app_etherpad

## Fonctionnalités spécifiques à YunoHost

#### Support multi-utilisateurs

 * L'authentification LDAP est-elle prise en charge ? **Non**
 * L'application peut-elle être utilisée par plusieurs utilisateurs ? **Oui**

#### Architectures supportées

* x86-64 - [![](https://ci-apps.yunohost.org/ci/logs/etherpad%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/etherpad/)
* ARMv8-A - [![](https://ci-apps-arm.yunohost.org/ci/logs/etherpad%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/etherpad/)

## Limitations

## Informations additionnelles

## Liens

 * Reporter un bug : https://github.com/YunoHost-Apps/etherpad_ynh/issues
 * Site d'Etherpad : http://etherpad.org/
 * Dépôt GitHub de l'application : https://github.com/ether/etherpad-lite
 * Site de YunoHost : https://yunohost.org/

---

## Informations à l'intention des développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/etherpad_ynh/tree/testing).

Pour tester la branche testing, merci de procéder ainsi.
```
sudo yunohost app install https://github.com/YunoHost-Apps/etherpad_ynh/tree/testing --debug
ou
sudo yunohost app upgrade etherpad -u https://github.com/YunoHost-Apps/etherpad_ynh/tree/testing --debug
```
