# IoT Edge. My tests on an Intel NUC

For an Intel Nuc with Grove IoT Commercial Developer Kit:

	• The default usr/pwd is : root / root

	• If you can connect to a wired network, connect the Arduino 101 with the LCD connected to an SPI port in the hat, you will see its IP address in a while


But, the Wind River installation does not have docker, so you will have to install an Ubuntu for the Nuc. First you need to setup the BIOS:

https://www.intel.com/content/www/us/en/support/articles/000022600/mini-pcs.html



And then install the Ubuntu:

https://developer.ubuntu.com/core/get-started/intel-nuc



For IoT Edge you need pip, to install it run

     > curl https://bootstrap.pypa.io/get-pip.py > get-pip.py

And then:

    > sudo python get-pip.py
