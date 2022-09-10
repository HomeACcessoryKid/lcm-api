(c) 2022 HomeAccessoryKid
 * LCM API used with LCM4ESP32

cd your-repo
git submodule add https://github.com/HomeACcessoryKid/lcm-api components/lcm-api

uint8_t lcm_read_count(); //read the restart count value from RTC
void    lcm_temp_boot(); //restart with RTC value of temp_boot active

