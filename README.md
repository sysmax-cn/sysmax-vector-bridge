# sysmax-vector-bridge
The SysMax Vector bridging tool is a tool software that establishes communication connections between virtual CAN devices in the Vector driver and real CAN/FD hardware to achieve a low-cost alternative to Vector CAN/FD devices.
## Introduce
This scheme realizes the compatibility of CAN interface devices with Vector software by accessing the Virtual CAN channel - Virtual CAN Channel of the Vector driver. This software Bridges the CAN/CAN FD data sent and received by the PCAN FD device with the Vector virtual CAN channel to achieve the purpose of communicating with the real physical bus through the Vector virtual CAN channel.
![alt text](image.png)
### User Case
 - The Vector software license has been obtained(or cracked), but a cost-effective hardware device is still needed as a substitute
 - There is already a Vector VN series device, but the number of CAN/FD channels is insufficient
 - Use free software developed based on the Vector driver (as follows), but also cost-effective hardware devices compatible with Vector are required
 - The software independently developed based on Vector XL-Driver-Library
 - Python CAN
 - TSmaster
## Hardware Support
 - Full CAN and CAN FD supported - SysMax PCAN FD (https://item.taobao.com/item.htm?id=673931783731)
 - Only CAN supported - PEAK PCAN-USB FD
## Usage