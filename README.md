# Philips Hue (ZigBee)

Control your Philips Hue devices with Homey using ZigBee!

## !!! Warning !!!

You need a dimming-switch to un-pair/reset bulps correctly from your Hue bridge or to reset your bulps in case something goes wrong during pairing. If you dont have one get one first before continuing!

Deleting a bulp from the Hue app or resetting your bridge will NOT work to un-pair/reset your lamps!

### Unpairing bulps from the Hue bridge

You will have to un-pair your bulp from the Hue bridge before you can pair it with Homey.

A Hue dimming-switch can be used to un-pair/reset a bulp using TouchLink.

First pair the bulp to the dimming-switch:

- Hold your dimming-switch in close proximity to the bulp and press the on-button for about 10 seconds.
- Keep holding the button while the bulp is blinking.
- The bulp is now paired to the dimming-switch

Now un-pair the light from the dimming-switch:

- Hold your dimming-switch in closely to the bulp and press the on-button and the off-button at the same time for about 10 seconds.
- Keep holding the buttons while the bulp is blinking.
- Your bulp is now un-paired and ready to be installed.

### Adding devices to Homey

I recommend adding devices using Homey \ ZigBee instead of selecting the device to add from the Hue app. That way the correct device will be selected automatically based on the interview.

### List of supported devices

- Ambiance Bulp
- Ambiance Spot
- Ambiance Ceiling
- Color Bulp
- Go
- Dimming-Switch

### Changelog

0.0.1
- Philips Hue (ZigBee) based on the Athom Osram Lightify app
