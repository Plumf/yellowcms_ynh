# Usage of this package (REMOVE THIS SECTION BEFORE RELEASE)
- Copy this app before working on it.
- Edit `conf/nginx.conf` file to match application prerequisites.
- Edit `manifest.json` with application specific information.
- Edit the `install`, `upgrade`, `remove`, `backup`, and `restore` scripts.
  - Using the [script helpers documentation.](https://helpers.yunohost.org/)
- Add a `LICENSE` file for the package.
- Edit `README.md` and README_fr.md.

# Example app for YunoHost

[![Integration level](https://dash.yunohost.org/yellowcms.svg)](https://dash.yunohost.org/appci/app/yellowcms)  
[![Install yellowcms with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=yellowcms)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allow you to install Yellow CMS quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview
Yellow is a CMS designed to make the creation of a website ultra-simple and easy to use. Yellow CMS does not require a database.
**Shipped version:** 0.8.11

## Screenshots

![](/images/yellowcms_screenshots.png)

## Demo

* [Official demo](https://datenstrom.se/edit/yellow/demo/)

## Configuration

How to configure this app: by an admin panel, a plain file with SSH, or any other way.

## Documentation

 * Official documentation: Link to the official documentation of this app
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-users support

Are LDAP and HTTP auth supported?
Can the app be used by multiple users?

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/yellowcms%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/yellowcms/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/yellowcms%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/yellowcms/)

## Limitations

* Any known limitations.

## Additional information

* Other information you would add about this application

**More information on the documentation page:**  
https://yunohost.org/packaging_apps

## Links

 * Report a bug: https://github.com/YunoHost-Apps/yellowcms_ynh/issues
 * App website: https://datenstrom.se/
 * Upstream app repository: https://github.com/datenstrom/yellow
 * YunoHost website: https://yunohost.org/

---

Developers info
----------------

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/yellowcms_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/yellowcms_ynh/tree/testing --debug
or
sudo yunohost app upgrade yellowcms -u https://github.com/YunoHost-Apps/yellowcms_ynh/tree/testing --debug
```
