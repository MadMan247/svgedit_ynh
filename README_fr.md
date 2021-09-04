# SVG-edit pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/svgedit.svg)](https://dash.yunohost.org/appci/app/svgedit) ![](https://ci-apps.yunohost.org/ci/badges/svgedit.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/svgedit.maintain.svg)  
[![Installer SVG-edit avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=svgedit)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer SVG-edit rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

SVG-edit is a fast, web-based, JavaScript-driven SVG drawing editor that works in any modern browser.

**Version incluse :** 5.1.0~ynh1

**Démo :** https://svg-edit.github.io/svgedit/dist/editor/index.html

## Captures d'écran

![](./doc/screenshots/screenshot.png)

## Documentations et ressources

* Site officiel de l'app : https://example.com
* Documentation officielle de l'admin : https://github.com/SVG-Edit/svgedit/tree/master/docs
* Dépôt de code officiel de l'app : https://github.com/SVG-Edit/svgedit
* Documentation YunoHost pour cette app : https://yunohost.org/app_svgedit
* Signaler un bug : https://github.com/YunoHost-Apps/svgedit_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/svgedit_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/svgedit_ynh/tree/testing --debug
ou
sudo yunohost app upgrade svgedit -u https://github.com/YunoHost-Apps/svgedit_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps