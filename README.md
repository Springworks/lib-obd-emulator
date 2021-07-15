# lib-obd-emulator
Library for sending commands to Freematics OBD-II Emulator.

# Setup
Recommended IDE: IntelliJ. Open pom.xml (Maven project).

The correct COM-port name needs to be provided to connect to the hardware emulator.

This has been tested on Windows and Linux.

For Windows (example: COM3), the COM-port name is shown in Device manager, COM-ports.

For Linux (example: /dev/ttyS0), check http://www.cyberciti.biz/faq/find-out-linux-serial-ports-with-setserial/

For macOS (COM-portname = tty.SLAB_USBtoUART), download device drivers from: https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers
