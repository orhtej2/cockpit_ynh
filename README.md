<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Cockpit for YunoHost

[![Integration level](https://dash.yunohost.org/integration/cockpit.svg)](https://dash.yunohost.org/appci/app/cockpit) ![Working status](https://ci-apps.yunohost.org/ci/badges/cockpit.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/cockpit.maintain.svg)

[![Install Cockpit with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cockpit)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Cockpit quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Cockpit is an interactive server admin interface. It is easy to use and very lightweight. Cockpit interacts directly with the operating system from a real Linux session in a browser.

**Shipped version:** 239~ynh1

## Screenshots

![Screenshot of Cockpit](./doc/screenshots/screenshot-storage.png)

## Documentation and resources

* Official app website: <https://cockpit-project.org/>
* Official admin documentation: <https://cockpit-project.org/documentation.html>
* Upstream app code repository: <https://github.com/cockpit-project/cockpit>
* YunoHost documentation for this app: <https://yunohost.org/app_cockpit>
* Report a bug: <https://github.com/YunoHost-Apps/cockpit_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/cockpit_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/cockpit_ynh/tree/testing --debug
or
sudo yunohost app upgrade cockpit -u https://github.com/YunoHost-Apps/cockpit_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
