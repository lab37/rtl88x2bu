# rtl88x2bu
Updated driver for rtl88x2bu wifi adaptors based on RTL88x2BU_WiFi_linux_v5.2.4.1_22719_COEX20170518-4444.20170613.

Build confirmed on kernels up to 4.14.0.

See http://www.wolfteck.com/2018/02/22/wsky_1200mbps_wireless_usb_wifi_adapter/ for all the hows and whys around the updates.
if error：macro ” __DATA__“ might prevetn 。。。。。
add the follow text to the ./Makefile
EXTRA_CFLAGS += -Wno-date-time 
