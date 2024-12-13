<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Plainpad voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/plainpad)](https://ci-apps.yunohost.org/ci/apps/plainpad/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/plainpad)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/plainpad)

[![Plainpad met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=plainpad)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Plainpad snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Plainpad is a self hosted, open source note taking application that is very easy to setup on your server. Your data will never leave your server and you will be able to access them from any device connected to the internet.
With Plainpad you can allow multiple users to access the application without being able to see each other's notes. The notes are being encrypted and stored safely in the database.

**Geleverde versie:** 1.0.0~ynh3

**Demo:** <https://alextselegidis.com/try/plainpad/#/login>

## Schermafdrukken

![Schermafdrukken van Plainpad](./doc/screenshots/screenshot.png)

## Documentatie en bronnen

- Officiele website van de app: <https://alextselegidis.com/get/plainpad>
- Officiele beheerdersdocumentatie: <https://alextselegidis.com/get/plainpad/self-hosted>
- Upstream app codedepot: <https://github.com/alextselegidis/plainpad>
- YunoHost-store: <https://apps.yunohost.org/app/plainpad>
- Meld een bug: <https://github.com/YunoHost-Apps/plainpad_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/plainpad_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/plainpad_ynh/tree/testing --debug
of
sudo yunohost app upgrade plainpad -u https://github.com/YunoHost-Apps/plainpad_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
