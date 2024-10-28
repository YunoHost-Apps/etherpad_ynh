<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# Etherpad para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/etherpad.svg)](https://ci-apps.yunohost.org/ci/apps/etherpad/) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/etherpad.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/etherpad.maintain.svg)

[![Instalar Etherpad con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=etherpad)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar Etherpad de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

Etherpad is a real-time collaborative editor scalable to thousands of simultaneous real time users. It provides full data export capabilities, and runs on your server, under your control.
This version of Etherpad is installed without plugins and uses Rustydb as database.
If you want to install Etherpad with plugins and MySQL database: https://github.com/YunoHost-Apps/etherpad_mypads_ynh


**Versión proporcionada:** 2.2.6~ynh1

**Demo:** <https://video.etherpad.com/>

## Capturas de pantalla

![Captura de pantalla de Etherpad](./doc/screenshots/screenshot.png)

## Documentación e recursos

- Web oficial da app: <https://etherpad.org/>
- Documentación oficial para admin: <https://etherpad.org/doc/v2.0.2/>
- Repositorio de orixe do código: <https://github.com/ether/etherpad-lite>
- Tenda YunoHost: <https://apps.yunohost.org/app/etherpad>
- Informar dun problema: <https://github.com/YunoHost-Apps/etherpad_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/etherpad_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/etherpad_ynh/tree/testing --debug
ou
sudo yunohost app upgrade etherpad -u https://github.com/YunoHost-Apps/etherpad_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
