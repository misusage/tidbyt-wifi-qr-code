# tidbyt-wifi-qr-code
A WiFi QR code app for the Tidbyt.

This app creates a scannable WiFi QR Code. It is currently not compatible with Enterprise networks as the Android/iPhone implementation is not adopted 100%. Also, there are display limitations with the Tidbyt and it's QR code library, so not all networks will be able to be encoded.

There are three things the app will ask you to provide:

1. Your WiFi SSID/Network name.
2. Your password.
3. The encryption method. Either WEP or WPA/WPA2/WPA3 (All WPA methods get encoded the same way).

If the QR code displays, then by simply scanning the QR code, your phone will join the network!

This app would be amazing to display in your home, bar, restaurant, and/or shop!

## Credits

I was inspired by [@evgeni's](https://github.com/evgeni) qifi project. His app is [here](https://qifi.org/).
