<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Etherpad untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/etherpad.svg)](https://ci-apps.yunohost.org/ci/apps/etherpad/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/etherpad.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/etherpad.maintain.svg)

[![Pasang Etherpad dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=etherpad)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Etherpad secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Etherpad is a real-time collaborative editor scalable to thousands of simultaneous real time users. It provides full data export capabilities, and runs on your server, under your control.
This version of Etherpad is installed without plugins and uses Rustydb as database.
If you want to install Etherpad with plugins and MySQL database: https://github.com/YunoHost-Apps/etherpad_mypads_ynh


**Versi terkirim:** 2.2.5~ynh1

**Demo:** <https://video.etherpad.com/>

## Tangkapan Layar

![Tangkapan Layar pada Etherpad](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://etherpad.org/>
- Dokumentasi admin resmi: <https://etherpad.org/doc/v2.0.2/>
- Depot kode aplikasi hulu: <https://github.com/ether/etherpad-lite>
- Gudang YunoHost: <https://apps.yunohost.org/app/etherpad>
- Laporkan bug: <https://github.com/YunoHost-Apps/etherpad_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/etherpad_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/etherpad_ynh/tree/testing --debug
atau
sudo yunohost app upgrade etherpad -u https://github.com/YunoHost-Apps/etherpad_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
