<img src="https://raw.githubusercontent.com/amitshekhariitbhu/awesome-android-things/master/awesome_android_things.png">

# Awesome Android Things [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Mindorks](https://img.shields.io/badge/mindorks-opensource-blue.svg)](https://mindorks.com/open-source-projects)
[![Mindorks Community](https://img.shields.io/badge/join-community-blue.svg)](https://mindorks.com/join-community)
>A curated list of awesome Android Things, tutorials, libraries and much more at one place. Here you can find references about everything you do during Android Things application development.

## Contents
  * [Useful links](#useful-links)
    * [Overview posts](#overview-posts)
    * [Introductions for Android developers](#introductions-for-android-developers)
    * [Sample apps and libraries](#sample-apps-and-libraries)
    * [Drivers](#drivers)
    * [TODO](#todo)
  * [Found this project useful <g-emoji alias="heart" fallback-src="https://assets-cdn.github.com/images/icons/emoji/unicode/2764.png" ios-version="6.0">❤️</g-emoji>](#found-this-project-useful-heart)
  * [Contact - Let's become friend](#contact---lets-become-friends)
  * [License](#license)
  * [Contributing](#contributing)

## Useful links

### Overview posts
- [What is Android Things](https://blog.mindorks.com/google-released-the-developer-preview-of-android-things-iot-75cb49b9ce24) - A complete explanation about Android Things.
- [Developer Kits](https://developer.android.com/things/hardware/developer-kits.html) - Discover the hardware platforms supported by Android Things as well as developer kits.
- [How to write an Android Things driver](https://www.novoda.com/blog/writing-your-first-android-things-driver-p1/) - Learn how to start writing drivers for peripherals to use with Android Things.
- [Threading Best Practices for Android Things](https://www.novoda.com/blog/threading-best-practices/)

### Introductions for Android developers
- [Android Things Tutorials — Getting Started](https://blog.mindorks.com/android-things-tutorials-getting-started-8464c11009ff) - Getting started with Android Things (Android Things Tutorial).
- [Get started with Android Things today!](https://www.androidthings.rocks/2017/01/03/get-started-with-android-things-today/) - How to install and build your first Android Things application using a Mac and a Raspberry Pi 3.
- [Learn about Peripheral I/O](https://developer.android.com/things/sdk/pio/index.html) - Know about the Peripheral I/O.
- [Android Things – Hardware Basics](https://riggaroo.co.za/android-things-hardware-basics/) - Hardware Basics for the Software Engineer.
- [Creating a driver](https://www.novoda.com/blog/writing-your-first-android-things-driver-p1/) - Writing your first Android Things driver.
- [Architect your Android Things applications](http://blog.blundellapps.co.uk/testing-android-things-iot-meets-java/) - How to architect your Android Things applications?

### Sample apps and libraries
- [drivers-sample](https://github.com/androidthings/drivers-samples) - Android Things driver samples: RGB LED strip (APA102), Temperature sensor (BMP280), Capacitive touch (CAP12xx), UART GPS, Segment display (HT16k33), Accelerometer (mma7660fc), PWM servo, PWM speaker, SSD1306 OLED display, 4-Digit Segment Display (tm1637), RainbowHat, SenseHat
- [New Project Template](https://github.com/androidthings/new-project-template) - Android Things empty project template.
- [CrunchyCalendar](https://github.com/CleverPumpkin/CrunchyCalendar) - A material calendar widget with infinite scrolling, date range selection and color customization.
- [sample-simplepio](https://github.com/androidthings/sample-simplepio) - Simple example of Android Things Peripheral I/O APIs.
- [sample-simpleui](https://github.com/androidthings/sample-simpleui) - Android Things Simple UI.
- [sample-button](https://github.com/androidthings/sample-button) - Button and LED sample for Android Things.
- [sample-uartloopback](https://github.com/androidthings/sample-uartloopback) - UART Loopback sample for Android Things.
- [sample-doorbell](https://github.com/androidthings/doorbell) - Android Things Doorbell sample.
- [sample-weatherstation](https://github.com/androidthings/weatherstation) - Android Things Weather Station sample.
- [sample-nativepio](https://github.com/androidthings/sample-nativepio) - 3 simple examples using native c++ peripheral IO API.
- [sample-tensorflow-imageclassifier](https://github.com/androidthings/sample-tensorflow-imageclassifier) - Android Things TensorFlow image classifier sample.
- [Serial Port Api](https://github.com/cepr/android-serialport-api) - A library to access serial ports in Android.
- [DoReFindMi](https://github.com/tomaszrykala/DoReFindMi) - Musical, button combination-finding game for [Rainbow HAT for Android Things](https://shop.pimoroni.com/products/rainbow-hat-for-android-things).
- [candle](https://github.com/Polidea/at_candle) - Simulation of a candle
- [native-libandroidthings](https://github.com/androidthings/native-libandroidthings) - Android Things Native Library.
- [Robot](https://github.com/euler2dot7/android_things_robot) - Android Things robot, controlled by web interface.
- [remote-barometer](https://github.com/SergiyKorotun/android-things-remote-barometer) - Android Things project using BMP-180 pressure sensor, Firebase and android mobile app for rendering data
- [example GPIO input](https://github.com/blundell/androidthings-gpio-input) - GPIO input (button) clean code sample 
- [example GPIO output](https://github.com/blundell/androidthings-gpio-output) - GPIO output (LED) clean code sample 
- [example PWM](https://github.com/blundell/androidthings-pwm) - PWM (speaker/buzzer) clean code sample 
- [example Speech-To-Text](https://github.com/Nilhcem/audiofun-androidthings/tree/pocketsphinx/) Speech-to-text with open source CMU Pocketsphinx recognizer.
- [codelab button-Firebase](https://github.com/danybony/android-things-button-sample) Codelab starting from button input to Firebase sync
- [Remote Storage](https://github.com/kevalpatel2106/remote-storage-android-things) - Create an FTP server using on raspberry pi and build your own wireless storage & backup solution for home.
- [Smart Switch](https://github.com/kevalpatel2106/smartswitch) - Control your home switches remotely from phone using Android Things & firebase realtime database.
- [Collision Detector](https://github.com/kevalpatel2106/collision-detector-android-things) - Get the distance of the object and alert using LED when object is too close using ultrasonic ranging sensor HC-SR04.
- [Smile Candy Machine](https://github.com/luisleao/smiledispenser) - Presented at Google I/O 2017 - a candy dispenser activated by smiles. Uses Google Cloud Vision API and Firebase.
- [sample-hd44780](https://github.com/leinardi/androidthings-drivers/tree/master/sample-hd44780) - This sample demonstrates how to control the HD44780 LCD using PCF8574's I2C with Android Things.
- [sample-lsm9ds1](https://github.com/leinardi/androidthings-drivers/tree/master/sample-lsm9ds1) - This sample demonstrates how to control the LSM9DS1 acceleration sensor and integrate it to the Android SensorManager.
- [sample-sh1106](https://github.com/leinardi/androidthings-drivers/tree/master/sample-sh1106) - This sample demonstrates how to control the SH1106 OLED display using I2C with Android Things.
- [sample-hcsr04](https://github.com/leinardi/androidthings-drivers/tree/master/sample-hcsr04) - This sample demonstrates how to control the HC-SR04 ultrasonic ranging module and integrate it to the Android SensorManager.
- [sample-softpwm](https://github.com/leinardi/androidthings-pio/tree/master/sample-softpwm) - This sample demonstrates how to control both software and hardware PWM.
- [sample-ds3231](https://github.com/leinardi/androidthings-drivers/tree/master/sample-ds3231) - This sample demonstrates how to control the DS3231 real-time clock (RTC) using I2C with Android Things.
- [Smart Room](https://github.com/carlosgub/Cuarto-Inteligente-Repo) - This sample shows how turn on/off a light by using a Relay and Firebase. / Este ejemplo muestra como prender y apagar la luz usando un relay y firebase
### Drivers
- [1602 LCD display](https://github.com/Nilhcem/1602A-androidthings) - 1602 LCD display
- [A4988](https://github.com/Polidea/Polithings/tree/master/a4988) - A4988 stepper motor driver
- [ADXL345 3-axis accelerometer](https://github.com/cagdasc/AndroidThings-ADXL345) - ADXL345 3-axis accelerometer
- [ADXL362 Accelerometer](https://github.com/vishal-android-freak/ADXL362-Interfacing-Library) - ADXL362 Accelerometer
- [Bosh BMP85/BMP180](https://github.com/euler2dot7/android_things_bmp180) - Bosh BMP85/BMP180 barometer
- [contrib-drivers](https://github.com/androidthings/contrib-drivers/) - Android Things Open source peripheral drivers: RGB LED strip (APA102), Temperature sensor (BMP280), Capacitive touch (CAP12xx), UART GPS, Segment display (HT16k33), Accelerometer (mma7660fc), PWM servo, PWM speaker, SSD1306 OLED display, 4-Digit Segment Display (tm1637), RainbowHat, SenseHat
- [DaSiAnThiLib](https://github.com/davemckelvie/things-drivers) - HD44870 type displays (via LCM1602), PCF8574(A), PCF8591, Push buttons connected via PCF8574, TCS34725 I2C Colour sensor
- [DS3231](https://github.com/leinardi/androidthings-drivers/tree/master/driver-ds3231) - real-time clock (RTC)
- [HC-SR04 Ultrasonic UserSensor](https://github.com/vishal-android-freak/HC-SR04-AndroidThings-Library) - HC-SR04 Ultrasonic UserSensor
- [HC-SR04](https://github.com/leinardi/androidthings-drivers/tree/master/driver-hcsr04) - ultrasonic ranging module
- [HC-SR501 Motion Sensor](https://github.com/blundell/PirMotionSensorModuleTut) - Motion Sensor Driver with creation tutorial
- [HCSR501 motion sensor](https://gist.github.com/PaulTR/0f09b2f8fdc2e45fa96aa53a77dabc05) - HCSR501 motion sensor
- [HD44780](https://github.com/leinardi/androidthings-drivers/tree/master/driver-hd44780) - alphanumeric dot matrix LCD
- [HMC5883L 3-axis magnetometer](https://github.com/cagdasc/AndroidThings-HMC5883L) - HMC5883L 3-axis magnetometer
- [keypad](https://github.com/Nilhcem/keypad-androidthings) - Matrix Keypad
- [ledcontrol](https://github.com/Nilhcem/ledcontrol-androidthings) - MAX72xx LED Matrix
- [LSM9DS1](https://github.com/leinardi/androidthings-drivers/tree/master/driver-lsm9ds1) - 3D accelerometer, 3D gyroscope, 3D magnetometer and temperature sensor
- [MCP3008](https://github.com/PaulTR/AndroidThingsMCP3008ADC) - Sample to use MCP3008 Analog to Digital Converter
- [MPR121](https://github.com/Nilhcem/mpr121-androidthings) - Proximity capacitive touch sensor
- [MPR121](https://github.com/the-cocktail/android-things-driver-mpr121) - MPR121 I2C touch sensor driver (tested on "Grove - I2C Touch Sensor")
- [numpad12](https://github.com/Polidea/Polithings/tree/master/numpad) - Numpad with 12 buttons
- [RFID-RC522](https://github.com/Galarzaa90/android-things-rc522) - RFID reader for MIFARE cards. Authentication, reading and writing.
- [SoftPwm](https://github.com/leinardi/androidthings-pio/tree/master/pio-softpwm) - Software PWM library for Android Things
- [Sparkfun](https://github.com/hcchoong79/androidthings) - Combined driver for the sparkfun blocks: OLEDBlock, LSM9DS0, UART
- [SH1106](https://github.com/leinardi/androidthings-drivers/tree/master/driver-sh1106) - OLED display
- [ULN2003](https://github.com/Polidea/Polithings/tree/master/uln2003) - 28BYJ-48 Stepper motor with ULN2003 driver
- [WS2801](https://github.com/xrigau/androidthings-ws2801-driver) - LED strips WS2801
- [BH1750](https://github.com/alvarowolfx/bh1750-androidthings) - Light sensor
- [TSL256x](https://github.com/leinardi/androidthings-drivers/tree/master/driver-tsl256x) - Light-to-digital sensor driver

### TODO
- Updating it on daily basis as much as possible so that we will be always updated.

### Found this project useful :heart:
* Support by clicking the :star: button on the upper right of this page. :v:

## Contact - Let's become friends
- [Twitter](https://twitter.com/amitiitbhu)
- [Github](https://github.com/amitshekhariitbhu)
- [Medium](https://medium.com/@amitshekhar)
- [Facebook](https://www.facebook.com/amit.shekhar.iitbhu)

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Amit Shekhar](https://github.com/amitshekhariitbhu) has waived all copyright and related or neighboring rights to this work.

## Contributing

Your contributions are always welcome! Just follow the following format: `[reference name](link) - Description.` If you like it, give a star to this project
