# m5stack-cores3-se-esp32-s3-rv32ima
[WIP] My fork of rv32ima linux emulator on M5Stack CoreS3 SE ESP32-S3, based on Epiczhul/esp32p4-rv32ima and cnlohr/mini-rv32ima

## CoreS3-SE
* https://docs.m5stack.com/en/core/CoreS3-SE
* Based on ESP32-S3 development, supports Wi-Fi @16MB Flash, 8MB PSRAM

## References
* https://github.com/weimingtom/m5stack-tab5-esp32-p4-rv32ima/tree/master/esp32p4-rv32ima
* https://github.com/Epiczhul/esp32p4-rv32ima
* https://github.com/cnlohr/mini-rv32ima
* https://github.com/weimingtom/wmt_riscv_study
* https://github.com/weimingtom/mini-rv32ima_fork
* https://github.com/xhackerustc/uc-rv32ima

## ESP-IDF version for **Win10 and Win11**
* ESP-IDF 5.4.4, for **Win10 and Win11**
* https://dl.espressif.cn/dl/esp-idf/
* https://dl.espressif.com/dl/idf-installer/esp-idf-tools-setup-offline-5.4.4.exe
* https://github.com/espressif/idf-installer/releases/download/offline-5.4.4/esp-idf-tools-setup-offline-5.4.4.exe
* https://github.com/espressif/esp-bsp/tree/master/examples
* https://github.com/m5stack/M5Tab5-UserDemo
* NOTE, not need ESP-IDF v5.4.2 (https://docs.espressif.com/projects/esp-idf/en/v5.4.2/esp32s3/index.html), ESP-IDF 5.4.4 is also good  
```
我测试过可以运行在m5stack tab5上运行的esp-idf示例代码有：
espressif/esp-bsp的examples和m5stack/M5Tab5-UserDemo。
另外我发现不必装ESP-IDF v5.4.2，只需要装5.4.4，效果是一样的，
只是5.4.4的安装程序没有显示ESP32P4的勾选，但不用管，
默认安装就可以，是可以设置目标板为esp32p4的 ​​​
```
* You should install **ONLY ONE** ESP-IDF instance on your computer at the same time, otherwise when you uninstall one of the ESP-IDF instances, the other instances will be unavailable (the shortcut will be deleted). It is recommended to reinstall the other ESP-IDF instances if you encounter similar situations
```
你应该在电脑上同时安装不多于一个ESP-IDF实例，
否则当你卸载其中一个ESP-IDF实例，
其他实例就不可用（快捷方式被删除），
建议如果遇到类似的情况最好重新安装其他ESP-IDF实例
```

