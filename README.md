# skytraq-datalogger
Forked from (https://code.google.com/p/skytraq-datalogger/).

This project is under GPLv2 License.

# Original README from the project page
Recently I bought a Skytraq DL-65 bluetooth GPS data logger (55 Euro). The provided software to read tracks from the device is a Windows program the "GPS Photo Tagger" from iTravel-Tech. But since I do not use Windows I needed a software for Linux to download track and configure the device.

When you connect the data logger via USB you can see that it uses a PL2303 USB-serial converter. Without any further software you can dump the NMEA data stream: cat /dev/ttyUSB0.

My device contains a SkyTraq Venus 6 GPS receiver. Older data loggers contain a Venus 5 GPS receiver. Those should also work with my program. The SkyTraq Venus uses a binary protocol to communicate with the host.
