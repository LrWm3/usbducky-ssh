# usbducky-ssh

Code to set up an [Adafruit Trinket](https://www.adafruit.com/product/1501) like a usbducky, where when plugged into a computer, it sets up an ssh server and installs your public key. Meant to be used to quickly add old junky computers to your network without having to fumble around with them to much. Don't use this for bad things

# How To Make this


[Navigate to this page](https://learn.adafruit.com/adafruit-arduino-ide-setup/arduino-1-dot-6-x-ide), install Arduino, then proceed to follow the remaining instructions to install the libraries for adafruit trinket.

Follow the instructions in this blog post by Eaton Chips in order to complete the rest of the project.
https://medium.com/@EatonChips/building-a-usb-rubber-ducky-for-7-c851aae30a1d

Finally, use [this Windows SSH server](https://null-byte.wonderhowto.com/how-to/create-native-ssh-server-your-windows-10-system-0181871/) reference to get rubber ducky to install or run the ssh server. Note that this may not actually be possible, because it might require admin privileges, but give it a shot anyway.

It would be cool to build it into the an actual USB key thing but who knows.

# LICENSE

MIT License
