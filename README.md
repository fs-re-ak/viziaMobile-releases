# viziaMobile-releases


## Release 2.1
* Improved BLE connection stability (2M Phy now being negotiated)
* Experiment id can be configured using QR Code
* Reverted EEG timestamping (needs post-process) to prevent timestamps overlaps, consequence of retrocalculation 


## Release 2.0 (BLE connectivity unreliable in challenging environment)
* Real-time data viewer
* Fixed audio recording (not all USB cameras are supported)
* MQTT controller integration
* Default operator consent
* API target can be configured
* New items in events at recording onset

## General
* Very important to deactivate location services. Keep location "on" for the GPS, but everything else should be turned off. Review these settings after each update.
