<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Etherpad pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/etherpad.svg)](https://ci-apps.yunohost.org/ci/apps/etherpad/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/etherpad.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/etherpad.maintain.svg)

[![Installer Etherpad avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=etherpad)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Etherpad rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Etherpad est un éditeur collaboratif en temps réel évolutif pour des milliers d'utilisateurs simultanés en temps réel. Il fournit des capacités complètes d'exportation de données et s'exécute sur votre serveur, sous votre contrôle.
Cette version d'Etherpad est installée sans plugins et utilise Rustydb (simple fichier) comme base de données.
Si vous souhaitez installer Etherpad avec les plugins et la base de données MySQL : https://github.com/YunoHost-Apps/etherpad_mypads_ynh",


**Version incluse :** 2.2.5~ynh1

**Démo :** <https://video.etherpad.com/>

## Captures d’écran

![Capture d’écran de Etherpad](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://etherpad.org/>
- Documentation officielle de l’admin : <https://etherpad.org/doc/v2.0.2/>
- Dépôt de code officiel de l’app : <https://github.com/ether/etherpad-lite>
- YunoHost Store : <https://apps.yunohost.org/app/etherpad>
- Signaler un bug : <https://github.com/YunoHost-Apps/etherpad_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/etherpad_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/etherpad_ynh/tree/testing --debug
ou
sudo yunohost app upgrade etherpad -u https://github.com/YunoHost-Apps/etherpad_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
