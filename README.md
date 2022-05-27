# Reyax-RYS8830-GPS-GNSS-Receiver-Module-guide
A small GPS/GNSS module comes with very low operating voltages, very helpful in retrieving time and date using satellites.
Get full info from here: https://www.instructables.com/Reyax-RYS8830-GPSGNSS-Receiver-Module-Guide/
JLCPCB:https://jlcpcb.com/SSR

In this post, we will learn how to use Reyax RYS8830 GPS/GNSS Receiver Module to retrieve time and position data from satellite navigation systems. The RYS8830 module from Reyax is based on Sony CXD5605GF/CXD5605AGF technology & comes as a small SMD component. The RYS8830 GNSS modules can be used in tracking devices that need to be small and power-saving. The Reyax RYS8830 has a small form factor and ultra-low power consumption. The GPS/GNSS Module can be interfaced with any microcontroller & can be operated using a simple coin-cell battery.

link to Reyax module: https://www.amazon.com/REYAX-RYS8830-Glonass-Antenna-Interface/dp/B0881LRJZ3
Link to Evo board: https://www.amazon.com/REYAX-RYS8830_EVB-Glonass-Antenna-Interface/dp/B09BMZJMD9

The RYS8830 Module is a very small SMD Module and requires a PCB. So, in this tutorial, we will use an evaluation board (RYS8830 EVB). The RYS8830 Evaluation Board has an embedded power circuit along with the CP2102 Chip & a micro-USB port. So the board can be directly connected to the computer and using the GNNS Software you can start learning and exploring the feature of RYS8830 Chip.

The performance of GNSS is assessed using four criteria:
1. Accuracy: the difference between a receiver’s measured and real position, speed, or time
2. Integrity: a system’s capacity to provide a threshold of confidence and, in the event of an anomaly in the positioning data, an alarm
3. Continuity: a system’s ability to function without interruption
4. Availability: the percentage of time a signal fulfills the above accuracy, integrity, and continuity criteria

Specifications
1. GNSS Center Frequency: 1561.098 MHz (BeiDou), 1575.42 MHz (GPS), 1602.5625 MHz (Glonass)
2. Navigation update rate: 1 Hz
3. Accuracy: up to 1m
4. Operating Temperature: -40°C to +85°C
5. Dimensions: 11mm*11mm*2.2mm
6. Power Supply Voltage: 1.8V
7. Satellite acquisition Current: 19 mA
8. Satellite tracking Current: 13 mA (GNSS continuous mode)
9. Satellite tracking Current: 2.6 mA to 8.2 mA (GNSS low power mode)
10. Idle Current: 3 mA (GNSS continuous mode)


GNSS Monitor Software For Customer:
The GNSS Monitor is a very useful software to evaluate GNSS receiver modules. Using this software, it is possible to connect to the modules to GNSS Transmitter by establishing a serial connection.
The software is very use to use and has user-friendly interface. You can download the software from the following link below:
Download: GNSS Monitor: https://drive.google.com/file/d/1-RwTI4yV2rxFE_6nxDds-myMlEw33d6v/view
After downloading the software, you can extract and install it on your PC System. During installation, you may encounter several issues that can be solved by installing proper framework drivers.

Circuit diagram is provided below with RYS8830 PDF. So, you may change the alignment, color and specifications of your PCB accordingly. Here in the circuit cp2102 USB TO Serial chip can be changed to some cheap solution like CH340G or FTDI232RL. Finally it's Depend on you and if you want to use same design then Download Gerber files from here. https://drive.google.com/drive/u/1/folders/1veFFKbvKDG9o7so9xhGJAqwyrxaZ9Nrr

You can order PCB prototypes from JLCPCB, providing 5 Pieces 2layer PCB in just $2. You can choose any color combination, thickness and surface finishing. And if you sign-up using this link, you will get free coupons of worth $30. Checkout JLCPCB right now and get your hands on best services, which may help you to turn your Ideas into Products. JLCPCB:https://jlcpcb.com/SSR

Important notice:
If you do not get any time or position data, please make sure that the antenna of the RYS8830 module is able to receive signals from the satellites. Usually, the GNSS receiver is not able to receive some signal when placed inside a building (e.g. onto your desk). I used a USB extension cable in order to be still able to work from my desk but having the RYS8830 EVB placed outside of the building.
