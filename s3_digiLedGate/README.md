# s3_digiLedGate OTA

Release rule: every new `s3_digiLedGate` firmware version must be published here.

For each release:

- build `s3_digiLedGate`
- copy the binary as `firmware-<version>.bin`
- update `latest.json`
- keep firmware version, manifest version, MD5, size, and URL in sync
- commit and push the OTA files to GitHub
