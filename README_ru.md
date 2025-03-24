<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Plainpad для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/plainpad)](https://ci-apps.yunohost.org/ci/apps/plainpad/)
![Состояние работы](https://apps.yunohost.org/badge/state/plainpad)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/plainpad)

[![Установите Plainpad с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=plainpad)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Plainpad быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Plainpad is a self hosted, open source note taking application that is very easy to setup on your server. Your data will never leave your server and you will be able to access them from any device connected to the internet.
With Plainpad you can allow multiple users to access the application without being able to see each other's notes. The notes are being encrypted and stored safely in the database.


**Поставляемая версия:** 1.0.0~ynh4

**Демо-версия:** <https://alextselegidis.com/try/plainpad/#/login>

## Снимки экрана

![Снимок экрана Plainpad](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://alextselegidis.com/get/plainpad>
- Официальная документация администратора: <https://alextselegidis.com/get/plainpad/self-hosted>
- Репозиторий кода главной ветки приложения: <https://github.com/alextselegidis/plainpad>
- Магазин YunoHost: <https://apps.yunohost.org/app/plainpad>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/plainpad_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/plainpad_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/plainpad_ynh/tree/testing --debug
или
sudo yunohost app upgrade plainpad -u https://github.com/YunoHost-Apps/plainpad_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
