<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Etherpad YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/etherpad)](https://ci-apps.yunohost.org/ci/apps/etherpad/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/etherpad)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/etherpad)

[![Instalatu Etherpad YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=etherpad)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Etherpad YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Etherpad is a real-time collaborative editor scalable to thousands of simultaneous real time users. It provides full data export capabilities, and runs on your server, under your control.
This version of Etherpad is installed without plugins and uses Rustydb as database.
If you want to install Etherpad with plugins and MySQL database: https://github.com/YunoHost-Apps/etherpad_mypads_ynh


**Paketatutako bertsioa:** 2.2.7~ynh1

**Demoa:** <https://video.etherpad.com/>

## Pantaila-argazkiak

![Etherpad(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://etherpad.org/>
- Administratzaileen dokumentazio ofiziala: <https://etherpad.org/doc/v2.2.7/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/ether/etherpad-lite>
- YunoHost Denda: <https://apps.yunohost.org/app/etherpad>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/etherpad_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/etherpad_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/etherpad_ynh/tree/testing --debug
edo
sudo yunohost app upgrade etherpad -u https://github.com/YunoHost-Apps/etherpad_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
