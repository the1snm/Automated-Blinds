# Automated Blinds

Moteino Shield requires a Moteino and a base station/bridge to work as shown in the example.

RFM69 Listening Mode Library: https://github.com/LowPowerLab/RFM69/tree/ListenMode

LowPower Library: https://github.com/LowPowerLab/LowPower

RFM Base station requires RFM69 library customization to work with D1 Mini Shield (https://github.com/hallard/WeMos-RFM69). Modified library file available in the /Arduino-Code/Libraries directory in this GitHub.

## Pin functions:

- **PWR** - Power Input (LiPo Battery Input)
- **A0** - Voltage level input (See Arduino Blinds code example on how to derive voltage from analog input)
- **A1** - 'CH' Signal Input from Solar Charger - Goes LOW when battery is charging
- **A2** - 'OK' Signal Input from Solar Charger - Goes LOW when battery is fully charged (~4.2V)           
- **D3** - Hardware Interrupt - Used to wake the Moteino when using the momentary switches for manual control
- **D4** - Switch 1 Input - Input from the momentary switch for manual control, direction of movement defined in code
- **D5** - Relay Output - Trips the mechanical relay to power the voltage booster and the servo
- **D6** - Servo Output - Sends commands to the attached servo
- **D7** - Switch 2 Input - Input from the momentary switch for manual control, direction of movement defined in code

----------

## Moteino Shield Schematic:

<img src="https://raw.githubusercontent.com/blebson/Automated-Blinds/master/Moteino-Shield-Schematic1.6.png" height="500">

<img src="https://cdn.tindiemedia.com/images/resize/eUsvWNJP5kUEZI7CQNCSk80Gej4=/p/full-fit-in/2400x1600/i/93677/products/2018-01-24T05%3A35%3A10.224Z-IMG_20180123_212950588.jpg" height="500">
