# Daily Fuel APK updates

This repository distributes approved Daily Fuel Android APK releases.
Application ID: `com.dailyfuel`.

The initial channel is a same-key, debug-signed update pilot. APK installation
always requires the user's approval through Android's package installer.

Release assets include the signed APK, update metadata, checksums and its public
signing certificate. The app verifies GitHub asset digests and requires the same
signing identity as the installed application. A certificate file cannot authorize
a signing-key change.

Application source code, private signing keys, credentials and user data/backups
must never be uploaded to this release repository.
