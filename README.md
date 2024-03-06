# ha-nanoleaf-4D
Modified HA Nanoleaf integration that adds basic support for the Nanoleaf 4D

Limitations:
Right now, Nanoleaf's API doesn't have events for when the 4D mode is changed. This means if 
it is changed from 1D to 2D in the Nanoleaf app for example, Home Assistant won't know until it asks 
the device which mode it is in.

## Install
You can install by either copying the repository link and use HACS or you can install manually 
by putting the custom_compnents/nanoleaf folder into your custom components folder
