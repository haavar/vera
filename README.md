# Sony Bravia TV plugin for vera
This is virtual device for turning on and off a sony TV.

Upload the LUUP file to vera.

Create a new device on the vera with these parameters:
  Device type: urn:schemas-upnp-org:device:BinaryLight:1
  Upnp Device Filename: D_BinaryLight1.xml
  Upnp Implementation Filename: I_BraviaTV.xml
  IP address: <ip address of your vera>
  
Set pre-shared key on your TV: [Settings] → [Network] → [Home Network Setup] → [IP Control] → [Pre-Shared Key] → [sony]

Go to the device on your vera (advance, variables) and set the password variable to the pre-shared key.
