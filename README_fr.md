# Yellow CMS pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/yellowcms.svg)](https://dash.yunohost.org/appci/app/yellowcms)  
[![Installer Yellow CMS avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=yellowcms)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer Yellow CMS rapidement et simplement sur un serveur Yunohost.  
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble
Yellow est un CMS conçue pour rendre la création d'un site internet ultra-simple et facile de prise en main. Yellow CMS ne necessite pas de base données.

**Version incluse:** 0.8.11

## Captures d'écran

![](/images/yellowcms_screenshots.png)

## Démo

* [Démo officielle](https://datenstrom.se/edit/yellow/demo/)

## Configuration

Comment configurer cette application: via le panneau d'administration, un fichier brut en SSH ou tout autre moyen.

## Documentation

 * Documentation officielle: Lien vers la documentation officielle de cette application
 * Documentation YunoHost: Si une documentation spécifique est nécessaire, n'hésitez pas à contribuer.

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateurs

L'authentification LDAP et HTTP est-elle prise en charge?
L'application peut-elle être utilisée par plusieurs utilisateurs?

#### Architectures supportées

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/yellowcms%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/yellowcms/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/yellowcms%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/yellowcms/)
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/ci/logs/yellowcms%20%28Apps%29.svg)](https://ci-stretch.nohost.me/ci/apps/yellowcms/)

## Limitations

* Limitations connues.

## Informations additionnelles

* Autres informations à ajouter sur cette application

**Plus d'informations sur la page de documentation:**  
https://yunohost.org/packaging_apps

## Liens

 * Signaler un bug: https://github.com/YunoHost-Apps/yellowcms_ynh/issues
 * Site de l'application: https://datenstrom.se/
 * Dépôt de l'application principale: https://github.com/datenstrom/yellow
 * Site web YunoHost: https://yunohost.org/

---

Informations pour les développeurs
----------------

**Seulement si vous voulez utiliser une branche de test pour le codage, au lieu de fusionner directement dans la banche principale.**
Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/yellowcms_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/yellowcms_ynh/tree/testing --debug
ou
sudo yunohost app upgrade yellowcms -u https://github.com/YunoHost-Apps/yellowcms_ynh/tree/testing --debug
```
