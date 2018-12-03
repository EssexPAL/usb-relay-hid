# usb-relay-hid (HW-554) Delphi 
![](http://vusb.wdfiles.com/local--files/project:driver-less-usb-relays-hid-interface/relay8.jpg)

Delphi GUI and command line source and applications to control an HW-554 USB relay card

The HW-554 relay card was purchased via eBay and came with no information or software, the suppliers were of little help.
Some digging on the internet indicated that it used USB HID.  pavel-a's repository (pavel-a/usb-relay-hid) on GitHub 
proved to be very useful source of information.

Getting Started
+ Download the projects into a suitable folder within your project structure.  Load the required project (e.g.relaycmd), 
change the search paths to include the path to your installation of the Jedi dcu, run and common folders.

Built with
+ Delphi
+ Jedi (jcl and Jvcl)

Author
+ Peter Lee

Acknowledgements - 
+ GitHub repository pavel-a/usb-relay-hid
+ Jedi Project HID TJvHidDeviceController and TJvHidDevice code written by Robert Marquardt.
