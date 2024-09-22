<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Etherpad для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/etherpad.svg)](https://ci-apps.yunohost.org/ci/apps/etherpad/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/etherpad.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/etherpad.maintain.svg)

[![Установите Etherpad с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=etherpad)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Etherpad быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Etherpad is a real-time collaborative editor scalable to thousands of simultaneous real time users. It provides full data export capabilities, and runs on your server, under your control.
This version of Etherpad is installed without plugins and uses Rustydb as database.
If you want to install Etherpad with plugins and MySQL database: https://github.com/YunoHost-Apps/etherpad_mypads_ynh",


**Поставляемая версия:** 2.2.5~ynh1

**Демо-версия:** <https://video.etherpad.com/>

## Снимки экрана

![Снимок экрана Etherpad](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://etherpad.org/>
- Официальная документация администратора: <https://etherpad.org/doc/v2.0.2/>
- Репозиторий кода главной ветки приложения: <https://github.com/ether/etherpad-lite>
- Магазин YunoHost: <https://apps.yunohost.org/app/etherpad>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/etherpad_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/etherpad_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/etherpad_ynh/tree/testing --debug
или
sudo yunohost app upgrade etherpad -u https://github.com/YunoHost-Apps/etherpad_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
