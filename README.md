SimpleSLIC is an expansion board for a KS0835 Subscriber Loop Interface Card.
This board makes it easy to serve a telephone line from any 3.3V or 5V
microcontroller.

![](/.readme/SimpleSLIC.jpg)

# Basic Use

1. Connect the Vcc pin to 3.3 or 5 Volts.
2. Connect the GND pin to ground.
3. Hook up a telephone to the phone jack.
4. To make the phone ring, pull the RM pin up to Vcc, and toggle the FR pin at
   20 Hz.

# Warning

This device is *NOT* intended to connect to a telephone line. Rather, this
device *is a phone line.* You connect phones and modems to this board, not other
phone lines. Likewise, do not connect two copies of this board directly together
by their phone jacks.

If you want to connect two boards together via their phone lines, use a pair of
600:600 audio transformers attached to the tip/ring pins of each board.

# Licensing

This project is licensed under the terms of CERN-OHL-S, Version 2. A copy of the
license can be found in the `LICENSE` file included in this repository.

This repository contains files from third-party sources. Such files are located
in the `Libraries/3rdparty` directory. Licensing information for these files has
been included with those files, when such information was provided by the
vendor.
