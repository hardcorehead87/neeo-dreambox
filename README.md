# NEEO-Dreambox
This Project allows the Control of any Enigma2 DVB Reciver with NEEO over TCP/IP

## Information about NEEO
- Please see https://neeo.com/ for more Information about NEEO The Thinking Remote
- For more about NEEOs SDK visit https://github.com/NEEOInc/neeo-sdk

## Requirements
- Change '$$LOCAL-IP' in controller.js to the locally assignes IP-Adress of your Enigma2 device e.g. 192.168.1.123
- Enabled WebIf on the Enigma2 device

- If Volume Control (Increase, Decrease and Mute) should be used on Enigma2 Reciver then delete /* and */ in controller.js line 40 and 55

# Changelog
## Version 0.0.3
- Merged dedicated Power ON / OFF into release (THX to hardcorehead87)
- Info Button added

## Version 0.0.2
- implemented breack after each button sent to prevent double input

## Version 0.0.1
- Initial release

## ToDo
- When the SDK get a list function it can be possbile to Enter the Movie readout or the actual EPG, let see what will come!