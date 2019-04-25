<b>
                          ================================
                          Running Sedona on a Raspberry Pi
                          ================================
</b>
  If you have a Raspberry Pi, you can make it a Sedona Device in just a few minutes!  

  See <a href='http://www.raspberrypi.org/faqs'>http://www.raspberrypi.org</a> to find out more about the Raspberry Pi, where 
  to get one, and how to do the initial setup.

  This archive includes native support for accessing the Raspberry Pi GPIO pins.


  1. Assumptions
  --------------
  It is assumed that the Raspberry Pi:

   * is running ArchLinux (may also work for other flavors of Linux)

   * has command line access, most commonly by ssh or telnet

   * has IP connectivity, and route exists to Niagara station or Sedona Workbench

   * can receive files over network (or copy to SD card)

   * is running a time service that syncs the device with network time (recommended)


  2. Sedona Device Setup
  ----------------------
    a. Copy this archive to the RPi (ssh, telnet, or direct copy to SD card).

    b. Extract the contents of the file.

    c. Move to the newly extracted folder, sedona-rpi/

    d. Start the Sedona VM as a background process:
         bin/svm --plat &


 Once the SVM is up and running, the device should be discoverable from your Niagara station 
 or Sedona Workbench through SedonaNetwork.  

