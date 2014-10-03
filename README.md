ble_app_hrs---LongWrite
=======================

Example on long write (long characteristic)
We can declare a characteristics with longer size than 20 bytes. Read and write more than 20 bytes would requires long write/read supported. 

The example based on the ble_app_hrs from SDK v6.1.
The Heart Rate Measurement characteristic to have longer size (QUEUED_WRITE_BUFFER_SIZE = 350), write and read properties added.
BLE_EVT_USER_MEM_REQUEST and BLE_EVT_USER_MEM_RELEASE events are handled. 
Can be tested with the Master Control Panel on PC or Android. 
Requirements
------------
- nRF51 SDK version 6.0+
- S110 v7.0+
- nRF51822 Development Kit version 2.1.0 or later

The project may need modifications to work with other versions or other boards. 

To compile it, clone the repository in the \nrf51822\Board\nrf6310\device_firmware_updates folder.

About this project
------------------
This application is one of several applications that has been built by the support team at Nordic Semiconductor, as a demo of some particular feature or use case. It has not necessarily been thoroughly tested, so there might be unknown issues. It is hence provided as-is, without any warranty. 

However, in the hope that it still may be useful also for others than the ones we initially wrote it for, we've chosen to distribute it here on GitHub. 

The application is built to be used with the official nRF51 SDK, that can be downloaded from https://www.nordicsemi.no, provided you have a product key for one of our kits.

Please post any questions about this project on https://devzone.nordicsemi.com.
