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
- LED and GND Connection: Connects via 5-pin JST Connector.
- Package: Minimized size design for optimal space utilization.
- Power Input: DC barrel jack input. Current input is 24V 1A and it works.
- Must support over-the-air firmware updates.
- Current firmware is based on WLED, but this selection is open since WLED may not support available dual-band WiFi (2.5G and 5G) and BLE controllers.
- PWM Control: 16 bit PWM switching
- Local Storage: Approximately 512KB to store essential data in case of device disconnection.
- Diagnostics: Status LEDs or tools to aid troubleshooting.
- Expected board dimensions on single-sided placement: Width preferably 20mm otherwise between 20mm - 30mm; Length can be increased as needed as long as it is technically suitable and helps achieve desired width

#### R+CCT Strip for Reference
![image](https://github.com/user-attachments/assets/8753e327-75df-42c4-9247-29d7966c8e57)


### Requirements for Extension Sub Board
- Covered by client himself. An outdated version is present in [this repo](https://github.com/eSpark-Consultants/benjamin-adapterboard).

### Requirements for Temination Board
- Allow user the ability to power from the opposite end of Main board without damaging any supply and safely power the MCU
- Contain barrel DC jack to supply input
- Contain JST connector to mate with the LED strip

#### PCB Layout Reference for Termination Board
![image](https://github.com/user-attachments/assets/56fbfccb-b895-4628-b176-300021e94c08)

## Unit Testing Main Controller Board - v1.1.0 
### Number of Assmebled Board received:  3 Boards 
### Number of Bare Boards received:  Nil

## Unit Testing Termination Board -v1.0.1
### Number of Assmebled Board received:  3 Boards 
### Number of Bare Boards received:  Nil
### Details of peripherals received: LED Strip with POGO Connector Female and Male Qty = 3

| S.No       | Board Name | Location (PK / Client) | Board Images (front / back / peripherals) |
| ----------- | ----------- |-------------| --- |
| 1      | Main Controller Board - v1.1.0   | PK |  https://drive.google.com/drive/folders/1u-aRuWP0ItrZxaj2FMrT51xFzzImfvsr |
| 2      | Termination Board -v1.0.1   | PK |  https://drive.google.com/drive/folders/18ihGvplU8rt-XHhBx0IHWcN0fZUaOvst |
| 3      | Peripherals   | PK |  https://drive.google.com/drive/folders/1fW_T0jg9QqRmtZ3q9VDzb-KoIyK4XJFM |
