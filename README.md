# Package Moved
This package has moved to the Laravel notification channels project. This repository will no longer be maintained. To switch, please see the "Migrating" section below. 

https://github.com/laravel-notification-channels/fcm

### Migrating
There are no breaking changes. The namespace will remain the same, so you only need to update your `composer.json` to reference the new package name, and bump the version to `1.6` (which has no breaking changes).

Switch the old package `require` from: 
```json
"require": {
    "coreproc/laravel-notification-channel-fcm": "^1.5"
},
```

to the new package name:
```json
"require": {
    "laravel-notification-channels/fcm": "^1.6"
},
```


## Laravel FCM (Firebase Cloud Messaging) Notification Channel

[![Latest Version on Packagist](https://img.shields.io/packagist/v/coreproc/laravel-notification-channel-fcm.svg?style=flat-square)](https://packagist.org/packages/coreproc/laravel-notification-channel-fcm)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE.md)
[![StyleCI](https://styleci.io/repos/91098630/shield)](https://styleci.io/repos/91098630)
[![SensioLabsInsight](https://img.shields.io/sensiolabs/i/621d780f-fdb7-479d-8fb2-683cbbc3ee4c.svg?style=flat-square)](https://insight.sensiolabs.com/projects/621d780f-fdb7-479d-8fb2-683cbbc3ee4c)
[![Quality Score](https://img.shields.io/scrutinizer/g/CoreProc/fcm.svg?style=flat-square)](https://scrutinizer-ci.com/g/CoreProc/fcm)
[![Total Downloads](https://img.shields.io/packagist/dt/coreproc/laravel-notification-channel-fcm.svg?style=flat-square)](https://packagist.org/packages/coreproc/laravel-notification-channel-fcm)


~This package makes it easy to send notifications using [Firebase Cloud Messaging](https://firebase.google.com/docs/cloud-messaging/) (FCM) with Laravel 5.3, 5.4, and 5.5.~
