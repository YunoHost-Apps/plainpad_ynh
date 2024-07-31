<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Plainpad YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/plainpad.svg)](https://ci-apps.yunohost.org/ci/apps/plainpad/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/plainpad.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/plainpad.maintain.svg)

[![Instalatu Plainpad YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=plainpad)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Plainpad YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Plainpad is a self hosted, open source note taking application that is very easy to setup on your server. Your data will never leave your server and you will be able to access them from any device connected to the internet.
With Plainpad you can allow multiple users to access the application without being able to see each other's notes. The notes are being encrypted and stored safely in the database.

**Paketatutako bertsioa:** 1.0.0~ynh3

**Demoa:** <https://alextselegidis.com/try/plainpad/#/login>

## Pantaila-argazkiak

![Plainpad(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://alextselegidis.com/get/plainpad>
- Administratzaileen dokumentazio ofiziala: <https://alextselegidis.com/get/plainpad/self-hosted>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/alextselegidis/plainpad>
- YunoHost Denda: <https://apps.yunohost.org/app/plainpad>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/plainpad_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/plainpad_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/plainpad_ynh/tree/testing --debug
edo
sudo yunohost app upgrade plainpad -u https://github.com/YunoHost-Apps/plainpad_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
