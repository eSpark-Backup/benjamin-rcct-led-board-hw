# RGB+CCT LED Strip Board Design
#### Client Name: Benjamin Voller-Brown

## Project Requirements
The project is for power, command and control of an RGB+CCT LED Strip. The board design will consist of three PCBs:
- Main Controller Board
- Power Sub Board
- Extension Sub Board

### Requirements for Main Controller Board
- Controller: Must include dual-band WiFi and Bluetooth connectivity.
- IOT Connectivity: Must be able to connect to other IOT devices or smart home systems.
- LED Length Function: Must work with LED strip over 6 meters in length without power injection.
- LED Connection: Connects via JST Connector.
- Package: Minimized size design for optimal space utilization.
- Power Input: DC barrel jack input. Current input is 24V 1A and it works.
- Must support over-the-air firmware updates.
- Current firmware is based on WLED, but this selection is open since WLED may not support available dual-band WiFi (2.5G and 5G) and BLE controllers.
- PWM Control: 16 bit PWM switching
- Local Storage: Approximately 512KB to store essential data in case of device disconnection.
- Diagnostics: Status LEDs or tools to aid troubleshooting.

### Requirements for Power Sub Board
TBD

### Requirements for Extension Sub Board
TBD
