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
