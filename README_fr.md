<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Plainpad pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/plainpad.svg)](https://dash.yunohost.org/appci/app/plainpad) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/plainpad.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/plainpad.maintain.svg)

[![Installer Plainpad avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=plainpad)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Plainpad rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Plainpad est une application de prise de notes open source auto-hébergée qui est très facile à configurer sur votre serveur. Vos données ne quitteront jamais votre serveur et vous pourrez y accéder depuis n'importe quel appareil connecté à Internet.
Avec Plainpad, vous pouvez autoriser plusieurs utilisateurs à accéder à l'application sans pouvoir voir les notes des autres. Les notes sont cryptées et stockées en toute sécurité dans la base de données. 

**Version incluse :** 1.0.2024.04.02~ynh1

**Démo :** <https://alextselegidis.com/try/plainpad/#/login>

## Captures d’écran

![Capture d’écran de Plainpad](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://alextselegidis.com/get/plainpad>
- Documentation officielle de l’admin : <https://alextselegidis.com/get/plainpad/self-hosted>
- Dépôt de code officiel de l’app : <https://github.com/alextselegidis/plainpad>
- YunoHost Store : <https://apps.yunohost.org/app/plainpad>
- Signaler un bug : <https://github.com/YunoHost-Apps/plainpad_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/plainpad_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/plainpad_ynh/tree/testing --debug
ou
sudo yunohost app upgrade plainpad -u https://github.com/YunoHost-Apps/plainpad_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
