(c) 2022 HomeAccessoryKid
 * LCM API used with [LCM4ESP32](https://github.com/HomeACcessoryKid/LCM4ESP32)

```
cd your-repo  
git submodule add https://github.com/HomeACcessoryKid/lcm-api components/lcm-api
```
Then copy the sdkconfig.defaults to your project directory.  
Do not forget to make your sdkconfig update if you already have one.  
Note that LCM uses custom[0] and custom[1] so you should use the custom entries after that if you need them.  
```
uint8_t lcm_read_count(); //read the restart count value from RTC  
void    lcm_temp_boot(); //restart with RTC value of temp_boot active  
```
