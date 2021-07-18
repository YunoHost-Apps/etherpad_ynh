# Etherpad pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/etherpad.svg)](https://dash.yunohost.org/appci/app/etherpad) ![](https://ci-apps.yunohost.org/ci/badges/etherpad.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/etherpad.maintain.svg)  
[![Installer Etherpad avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=etherpad)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Etherpad rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Éditeur en ligne fournissant l'édition collaborative en temps réel.

**Version incluse :** 1.8.13~ynh1

**Démo :** https://video.etherpad.com/

## Documentations et ressources

* Site officiel de l'app : https://etherpad.org/
* Documentation officielle utilisateur : https://yunohost.org/en/app_etherpad
* Documentation officielle de l'admin : http://etherpad.org/doc/v1.8.13
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