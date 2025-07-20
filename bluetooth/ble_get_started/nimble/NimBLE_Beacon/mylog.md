myLog
```

``` nginx
pi@raspberrypi:~/espExTest/bluetooth/nimble $ . $HOME/esp/v5.3.3/esp-idf/export.sh
...
pi@raspberrypi:~/espExTest/bluetooth/nimble $ ls /dev/ttyUSB*
/dev/ttyUSB0
pi@raspberrypi:~/espExTest/bluetooth/ble_get_started/nimble/NimBLE_Beacon $ ls
CMakeLists.txt  main  README.md  sdkconfig.defaults
pi@raspberrypi:~/espExTest/bluetooth/ble_get_started/nimble/NimBLE_Beacon $ idf.py build flash monitor 
...
```
``` nginx
I (449) main_task: Started on CPU0
I (459) main_task: Calling app_main()
I (479) BTDM_INIT: BT controller compile version [dc1cd58]
I (479) BTDM_INIT: Bluetooth MAC: 80:f3:da:55:1f:f2
I (479) phy_init: phy_version 4860,6b7a6e5,Feb  6 2025,14:47:07
I (789) NimBLE_Beacon: nimble host task has been started!
I (789) main_task: Returned from app_main()
I (829) NimBLE_Beacon: device address: F2:1F:55:DA:F3:80
I (839) NimBLE: GAP procedure initiated: advertise; 
I (839) NimBLE: disc_mode=2
I (839) NimBLE:  adv_channel_map=0 own_addr_type=0 adv_filter_policy=0 adv_itvl_min=0 adv_itvl_max=0
I (839) NimBLE: 

I (849) NimBLE_Beacon: advertising started!

```
