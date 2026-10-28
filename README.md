# viziaMobile-releases

<img width="410" height="410" alt="viziaMobileRelease" src="https://github.com/user-attachments/assets/71f0e656-b91a-4fb3-b019-64a9f510f6fa" />

## Release 2.4.0
* Positioning as a device (GPS/UWB)
* UWB positioning (DWM1001) integration
* Intake survey before a session, 
* French consent and survey strings, language picker for those documents, 
* Experiment-document download with an offline cache, 
* Bluetooth scan filter, 
* Erase-local-data-after-upload
* Always reconnecting
* Headset motion uploads as MOTION and Shimmer gyro as GYRO
* Live streaming of session CSV files to the server while recording

## Release 2.3.0
* Auto-revoke consent after each recording.
* Robust mode: optionally require the headset, wristband, or camera to be connected before a recording can start.
* Optional unique ID on the consent form.

## Release 2.2.2
* MQTT fixes:
  * No longer need to be on record page
  * Fixed ghost session creation on stop recording

## Release 2.2
* integrated Shimmer3R (legacy support untouched)
* IMU is now scaled to physical units

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
