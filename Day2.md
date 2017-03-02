# Day two of the TopConf17

## Opening Open Source with DevOps
Put stuff in containers and virtual images so that open source is easy for everybody to contribute!

* Ansible
* Vagrant
* Docker easy from the command line (every app in one docker container and manage them with docker compose)
* GitLab
* chef omnibus

**how can DEVOPS make OPENSOURCE more open?**
* Create confidence inspiring test environments
* Developer setup effortless
* Distribute painless setup tools

`@pimterry` on twitter – working at [resin.io](https://resin.io)


## Nativescript 2 with Angular 2 – leveraging the full power of native
Native support for GPS, Camera Geo Location, Gyro Sensors. Webapp is nice but it doesn't fell native it is a compromise
So we have hybrid frameworks -> ends up in a App store (Ionic, Cordova, Titanium, Phonegap, React Native) -> the problem you need to learn the api and you have limited access to hardware but what you build is not really native.

**Progressive Web apps!**
* Feels like an app
* Caches -> the power of **Service Workers!** (sw-toolbox.js)
* Push notifications
* Progressive enhancements *better features with better browsers and better broadband*
* Not great support on Safari yet

### Nativescript:
* It's not web , so no DOM
* It targets actual apis
* It supports hardware due to being actual native
* but you can use javascript and css

**killer features**
* you can style with css
* you can use javascript or angular2 with typescript
* hardware accelerated animations
* you can monetize because you have the appstore
* It's pluggable you can use and write own plugins

Android   | IOS
----------|----------------
V8        | JavaScriptCore

NativeScript inject android/ios stuff on runtime!

```javascript
  android.text.format.Time()
```
involkes a callback that native script can intercept, and *corresponding c++ callback*

**Nativescript consists of modules**
```
node_modules/tns-core-modules
            ...camera... /  camera.android.js
                            camera.ios.js
                            camera-common.js
```

How to install? `npm i nativescript -g`

create own app: `tns create my-app-name --ng` (--ng) flag for angular app

**it is just angular2** with a component layer



## Frequent Releases & Major Changes
12:00 – Ursulinensaal

## I have a stream – Insights in Reactive Programming
13:40 – Clubgallerie
