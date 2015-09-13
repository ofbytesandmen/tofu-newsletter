# tofu-newsletter
a simple newsletter implemented with nodejs and mongodb.

## requirements
- mongodb
- nodejs (modules: express, body-parser, mongojs)

## config
the following configuration values are currently in main.js
- set mongoDBName
- choose a port for the app
- change newsletterName, siteName, and newsletterDescription

## run
you can type:
```
nodejs main.js
```
or if you're using forever
```
forever start main.js
```
