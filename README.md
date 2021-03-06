Push Notifications
==================

## apns.sh

#### Requirements

* Bundled certificates for VoLTE & VoWiFi, named **volte.pem** & **vowifi.pem** respectively.
* A properly configured **.variables** file defining the respective Bundle ID/Toptic for VoLTE & VoWiFi.

#### Notes

* Token can be Base64 or HEX.
* Examples are **9XaWP5hwQ2nMwTEVvTuvTG9bum7t/PiphrOjdqfwot8=** for Base64 and **F576963F98704369CCC13115BC5BA44C6F5BBA6EEDFCF8A986B3A376A7F0A2DF** for HEX.

#### Usage

```
./apns.sh <TOKEN> <VoLTE|VoWiFi>
```

## fcm.sh

#### Requirements

* A properly configured **.variables** file defining the FCM Server Key.

#### Notes

* Example of a token is clKnhZRv4Dg:APA91bH6zi_leSdYHLYfuQtA3-3u7XjloGn76PQgTQu0dsOIWcWiWCBKV6uAeRMFzHKoFFpzOprymWIDxQLCZw7-k4KnXcvITccHragl12Vyozlt0ZvsmDW2X6cO39xoOqJWp9wdhNKQ

#### Usage

```
./fcm.sh <TOKEN> <VoWiFi>
```
