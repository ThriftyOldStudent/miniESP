# miniESP - The most basic ESP WROOM-32D interface board
This is a simplified version of the board design of ESP32 dev kit C v4 according to Espressif site: [https://dl.espressif.com/dl/schematics/esp32_devkitc_v4-sch.pdf](https://dl.espressif.com/dl/schematics/esp32_devkitc_v4-sch.pdf)  
The purpose of this repository is just as my own portfolio, just to showcase that I know how to draw schematic, do placement, draw layout, generate gerber using KiCAD. I can do even more complicated job with KiCAD and Eagle and whatever in house CAD. But if you find the content helpful for your study, do feel free to use it. Please do not ask me for the KiCAD files, as they are very simple, with all the information in this repo, you may generate the file yourself without problem. There are plenty of tutorials out there you may google them to learn how to use KiCAD. Wish you good luck for your assignments and projects (for all the students out there who stumble across this repo.)

# Schematic
![](https://raw.githubusercontent.com/ThriftyOldStudent/miniESP/main/miniESP32.png)
# Bill of Material (BOM)
| Reference      | Value | Footprint |
| ----------- | ----------- | ----------- |
| >  C1, C4, C5	 | 1n	 | Capacitor_SMD:C_0402_1005Metric |
|    C2	 | 100u	 | Capacitor_SMD:C_1206_3216Metric |
|    C3	 | 1u	 | Capacitor_SMD:C_0402_1005Metric |
|    J1	 | Conn_01x06_Male	 | Connector_PinHeader_2.54mm:PinHeader_1x06_P2.54mm_Vertical |
| >  J2, J3 | 	Conn_02x06_Odd_Even	 | Connector_PinHeader_2.54mm:PinHeader_2x10_P2.54mm_Vertical_SMD |
| >  Q1, Q2	 | S8050	 | Package_TO_SOT_SMD:SOT-23 |
| >  R1, R9, R10	 | 12k	 | Resistor_SMD:R_0805_2012Metric |
| >  R2, R3	 | 5k	 | Resistor_SMD:R_0805_2012Metric |
| >  R4, R11	 | 470	 | Resistor_SMD:R_0805_2012Metric |
| >  R5, R6	 | 0	 | Resistor_SMD:R_0402_1005Metric |
|     SW1	 | EN | 	Button_Switch_SMD:SW_Push_SPST_NO_Alps_SKRK |
|     SW2	 | BOOT	 | Button_Switch_SMD:SW_Push_SPST_NO_Alps_SKRK |
|    U1	 | ESP32-WROOM-32D	 | ESP32-WROOM-32 |

# Layout
![]()
# 3D
![](https://raw.githubusercontent.com/ThriftyOldStudent/miniESP/main/miniESP32_3d_front.png)
![](https://raw.githubusercontent.com/ThriftyOldStudent/miniESP/main/miniESP32_3d_back.png)
