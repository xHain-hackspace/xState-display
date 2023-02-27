# xState Display

This is a [ESP Home](https://esphome.io/) project for the inklpate display in the door.

To build this project follow the tutorial [here](https://esphome.io/guides/getting_started_command_line.html) and run:

`esphome run xhain.yaml`

with the board attached via USB. There is also the possibility to use OTA updates.

## Secrets

Please make a file from this template called `secrets.yaml` in the root directory of this repository.

```yaml
# Secrets file for xState display
wifiSSID: "<SSID>"
wifiPass: "<supersecretPassword>" 
fallbackPass: "<evenmoresecretPassword>"
apiPass: "<password>"
otaPass: "<password>"
```
