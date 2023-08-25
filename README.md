<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Umami for YunoHost

[![Integration level](https://dash.yunohost.org/integration/umami.svg)](https://dash.yunohost.org/appci/app/umami) ![Working status](https://ci-apps.yunohost.org/ci/badges/umami.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/umami.maintain.svg)

[![Install Umami with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=umami)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Umami quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Umami is a simple, easy to use, self-hosted web analytics solution. The goal is to provide you with a friendlier, privacy-focused alternative to Google Analytics and a free, open-sourced alternative to paid solutions. Umami collects only the metrics you care about and everything fits on a single page. 

### Features

- Simple analytics
- Unlimited websites
- Bypass ad-blockers
- Light-weight
- Multiple accounts
- Share data
- Mobile-friendly
- Data ownership
- Privacy-focused


**Shipped version:** 2.5.0~ynh2

**Demo:** https://app.umami.is/share/8rmHaheU/umami.is

## Screenshots

![Screenshot of Umami](./doc/screenshots/dark.png)

## Documentation and resources

* Official app website: <https://umami.is/>
* Official admin documentation: <https://umami.is/docs/about>
* Upstream app code repository: <https://github.com/mikecao/umami>
* YunoHost documentation for this app: <https://yunohost.org/app_umami>
* Report a bug: <https://github.com/YunoHost-Apps/umami_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/umami_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/umami_ynh/tree/testing --debug
or
sudo yunohost app upgrade umami -u https://github.com/YunoHost-Apps/umami_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
