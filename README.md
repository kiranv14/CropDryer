# CropDryer
Small scale automatic crop drying system for quick and efficient crop drying. We aim to have a hardware setup which can maintain optimal air flow, temperature and humidity in a 100 Liter chamber which is required by the crop loaded in chamber. The chamber should be thermally sealed with venting fans to control internal conditions. 

The drying may be done in batches in predefined cycles. To improve efficiency, we would aim to keep the chamber closed for as long as possible and vent controlled amount of air to maintain humidity below allowed threshold. 

## Hardware Setup
- HT101 Temperature and humidity sensor
- 100W Light bulb as heat source
- 12V BLDC fan x 2 for internal air flow and external air vent control
- Generic webcam device for monitoring drying progress. The webcam data may also be used to aid in estimating drying progress, smoke or steam detection
- Wifi smart plug for energy consumption monitoring
- Raspberry Pi 4B as prototyping controller(for learning phase) which has to be replaced with another MCU in long run
