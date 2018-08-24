#Token App

## Setup environment

### Cloud Foundary Login:
```
cf login -sso -a https://api.cf.eu1.mindsphere.io
```

## Push the app:

```
cf push
```

## Create and register the application in Developer Copckpit

### Create the application
* Name: tokenVendor
* Display Name: Token Vendor
* Version: 1.0.0
* Icon: is needed
* Components
  * Name: ui
  * Cloud Foundry Direct URL: https://token-vendor-xxxxxxx.apps.eu1.mindsphere.io
  * Endpoint: /**

Click on button *Save*

### Register the application
Open the app again and click on button *Register*

## Add the application scope to your user
Go to *User Management*, search for you user and add the right scope


