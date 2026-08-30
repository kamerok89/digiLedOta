# digiLed Gate OTA

Każda nowa wersja firmware i portalu `digiLed Gate` musi zostać opublikowana w tym katalogu.

For each release:

- build `digiLed Gate`
- copy the binary as `firmware-<version>.bin`
- copy the portal as `littlefs-<version>.bin`
- create `digiLed Gate-<version>.dgu`
- update `latest.json`
- keep firmware version, manifest version, MD5, size, and URL in sync
- commit and push the OTA files to GitHub
