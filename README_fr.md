# Application vide avec accès SFTP au répertoire Web personnalisé pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/my_webapp.svg)](https://dash.yunohost.org/appci/app/my_webapp) ![](https://ci-apps.yunohost.org/ci/badges/my_webapp.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/my_webapp.maintain.svg)  
[![Installer Custom Webapp avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=my_webapp)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer une Application vide avec accès SFTP au répertoire Web personnalisé rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Cette application vous permet d'installer facilement une application vide personnalisée,
fourni un accès aux fichiers avec [SFTP](https://yunohost.org/#/filezilla). Elle peut également créer une base de données MySQL -
qui sera sauvegardée et restaurée avec votre application. Les détails de connexion
seront stockés dans le fichier `db_accesss.txt` situé dans le répertoire racine.

**Version incluse :** 1.0

## Configuration

## Documentation

 * Documentation YunoHost : https://yunohost.org/#/app_my_webapp

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateurs

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/my_webapp.svg)](https://ci-apps.yunohost.org/ci/apps/my_webapp/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/my_webapp.svg)](https://ci-apps-arm.yunohost.org/ci/apps/my_webapp/)

## Limitations

## Informations additionnelles

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/my_webapp_ynh/issues
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request dans la [branche testing](https://github.com/YunoHost-Apps/my_webapp_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/my_webapp_ynh/tree/testing --debug
ou
sudo yunohost app upgrade my_webapp -u https://github.com/YunoHost-Apps/my_webapp_ynh/tree/testing --debug
```
