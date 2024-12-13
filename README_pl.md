<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# Plainpad dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/plainpad)](https://ci-apps.yunohost.org/ci/apps/plainpad/)
![Status działania](https://apps.yunohost.org/badge/state/plainpad)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/plainpad)

[![Zainstaluj Plainpad z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=plainpad)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację Plainpad na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

Plainpad is a self hosted, open source note taking application that is very easy to setup on your server. Your data will never leave your server and you will be able to access them from any device connected to the internet.
With Plainpad you can allow multiple users to access the application without being able to see each other's notes. The notes are being encrypted and stored safely in the database.

**Dostarczona wersja:** 1.0.0~ynh3

**Demo:** <https://alextselegidis.com/try/plainpad/#/login>

## Zrzuty ekranu

![Zrzut ekranu z Plainpad](./doc/screenshots/screenshot.png)

## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://alextselegidis.com/get/plainpad>
- Oficjalna dokumentacja dla administratora: <https://alextselegidis.com/get/plainpad/self-hosted>
- Repozytorium z kodem źródłowym: <https://github.com/alextselegidis/plainpad>
- Sklep YunoHost: <https://apps.yunohost.org/app/plainpad>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/plainpad_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/plainpad_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/plainpad_ynh/tree/testing --debug
lub
sudo yunohost app upgrade plainpad -u https://github.com/YunoHost-Apps/plainpad_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
