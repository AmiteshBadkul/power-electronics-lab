## About
The model presents Battery charging/discharging Control implemented in a case study that involves a DC bus (with a constant voltage), 
battery, a common load, and a bidirectional two-switch Buck-Boost DC-DC converter.

The control of battery charging and discharging is based on two PI controllers:
1- one is for reference current generation (dependant on mode of operation: charging or discharging)
2- The other is for Current control of the battery.
The presented case study includes two modes of operation:
1-Charging mode: automatically activated when the DC bus is connected and the control objective i.e: set point (of the 1st PI closed loop) becomes the full voltage of the battery.
2-Discharging mode: automatically activated when the DC bus is NOT connected and the control objective (of the 1st PI closed loop) becomes load voltage in order to maintain a constant load voltage during discharging.

Battery Power Flow control model  consists of :
- Battery
- DC voltage source
- Bidirectional DC to DC converter (Buck boost)
- Common load for two sources


## References
1. Haque, M. R., & Razzak, M. A. (2021, April). A Buck Converter-based Battery Charging Controller for Electric Vehicles using Modified PI Control System. In 2021 IEEE International IOT, Electronics and Mechatronics Conference (IEMTRONICS) (pp. 1-4). IEEE.
2. Patel, J., Chandwani, H., Patel, V., & Lakhani, H. (2012, March). Bi-directional DC-DC converter for battery charging—Discharging applications using buck-boost switch. In 2012 IEEE Students' Conference on Electrical, Electronics and Computer Science (pp. 1-4). IEEE.
