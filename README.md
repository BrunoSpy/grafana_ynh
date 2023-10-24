<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Grafana for YunoHost

[![Integration level](https://dash.yunohost.org/integration/grafana.svg)](https://dash.yunohost.org/appci/app/grafana) ![Working status](https://ci-apps.yunohost.org/ci/badges/grafana.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/grafana.maintain.svg)

[![Install Grafana with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=grafana)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Grafana quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Grafana is a multi-platform open source analytics and interactive visualization web application. It provides charts, graphs, and alerts for the web when connected to supported data sources.

**Shipped version:** 10.1.5~ynh1

**Demo:** https://play.grafana.org

## Screenshots

![Screenshot of Grafana](./doc/screenshots/Grafana8_Kubernetes.jpg)

## Documentation and resources

* Official app website: <https://grafana.com/>
* Upstream app code repository: <https://github.com/grafana/grafana>
* Report a bug: <https://github.com/YunoHost-Apps/grafana_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/grafana_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/grafana_ynh/tree/testing --debug
or
sudo yunohost app upgrade grafana -u https://github.com/YunoHost-Apps/grafana_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
