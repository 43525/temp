mylog
---
``` nginx
pi@raspberrypi:~/espExTest/bluetooth/ble_get_started/bluedroid/Bluedroid_Connection $ idf.py build flash monitor
...
I (511) coexist: coex firmware version: 85a8de8
I (516) main_task: Started on CPU0
I (526) main_task: Calling app_main()
I (546) BTDM_INIT: BT controller compile version [dc1cd58]
I (546) BTDM_INIT: Bluetooth MAC: 80:f3:da:55:1f:f2
I (556) phy_init: phy_version 4860,6b7a6e5,Feb  6 2025,14:47:07
I (936) CONN_DEMO: GATT server register, status 0, app_id 0
I (936) main_task: Returned from app_main()
I (936) CONN_DEMO: Advertising data set, status 0
I (956) CONN_DEMO: Advertising start successfully
I (23196) CONN_DEMO: Connected, conn_id 0, remote 69:f7:4b:22:3c:d9
I (23526) CONN_DEMO: Connection params update, status 0, conn_int 24, latency 0, timeout 400
I (23786) CONN_DEMO: Connection params update, status 0, conn_int 6, latency 0, timeout 500
I (23916) CONN_DEMO: Connection params update, status 0, conn_int 24, latency 0, timeout 400
W (67766) BT_HCI: hcif disc complete: hdl 0x0, rsn 0x13
I (67766) CONN_DEMO: Disconnected, remote 69:f7:4b:22:3c:d9, reason 0x13
I (67776) CONN_DEMO: Advertising start successfully
```
