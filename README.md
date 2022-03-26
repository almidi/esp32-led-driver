# ESP32 Led Driver
ESP32 based 4-channel led driver for home automation.
Schematics and PCB design where originally developed on EasyEDA.
This example uses ESP-Home for integration with HomeAssistant.

![ESP32 Led Driver PCB](/images/pcb-3d.png "ESP32 Led Driver PCB")


## BOM

|ID	    |Name	                 |Designator	         |Footprint	                            |Quantity	|Manufacturer Part	    |Manufacturer   |
|-------|------------------------|-----------------------|--------------------------------------|-----------|-----------------------|---------------|
| 1 	|10uF 	                 |C1 	                 |C0805 	                            |1 	        |CL21A106KAYNNNE 	    |SAMSUNG        |
| 2 	|22uF 	                 |C2 	                 |C0603 	                            |1 	        |CL10A226MQ8NRNC 	    |SAMSUNG        |
| 3 	|22nF 	                 |C3 	                 |C0603 	                            |1 	        |CL10B223KB8NNNC 	    |SAMSUNG        |
| 4 	|47uF 	                 |C4 	                 |CAP-SMD_BD5.0-L5.3-W5.3-RD 	        |1 	        |VES470M1CTR-0505 	    |Lelon          |
| 5 	|100pF 	                 |C6 	                 |C0603 	                            |1 	        |CL10C101JB8NNNC 	    |SAMSUNG        |
| 6 	|B230A-13-F 	         |D1 	                 |SMA_L4.4-W2.6-LS5.0-RD 	            |1 	        |B230A-13-F 	        |DIODES         |
| 7 	|DC-005-5A-2.0 	         |DC1 	                 |DC-IN-TH_DC-005-5A-2.0 	            |1 	        |DC-005-5A-2.0 	        |XKB Enterprise |
| 8 	|TS-1187A-B-A-B 	     |FLASH,RST 	         |SW-SMD_4P-L5.1-W5.1-P3.70-LS6.4 	    |2 	        |TS-1187A-B-A-B 	    |XKB Enterprise |
| 9 	|Top Header 	         |J1 	                 |HDR-TH_20P-P2.54-V 	                |1 	        |2.54mm 1*20PHeader 	|BOOMELE        |
| 10 	|Bottom Header 	         |J2 	                 |HDR-TH_20P-P2.54-V 	                |1 	        |2.54mm 1*20PHeader 	|BOOMELE        |
| 11 	|3.3uH 	                 |L1 	                 |IND-SMD_L4.2-W4.4_MWSA0402S-XX 	    |1 	        |MWSA0402S-3R3MT 	    |Sunlord        |
| 12 	|0603White light_C2290 	 |LED1 	                 |LED0603-R-RD 	                        |1 	        |0603White light 	    |KENTO          |
| 13 	|KIA30N06BD 	         |Q1,Q2,Q3,Q4 	         |TO-252-2_L6.6-W6.1-P4.57-LS9.9-TL-CW 	|4 	        |KIA30N06BD 	        |KIA            |
| 14 	|1K 	                 |R1,R4,R5,R6,R7,R8,R9 	 |R0603 	                            |7 	        |0603WAF1001T5E 	    |UniOhm         |
| 15 	|100 	                 |R2 	                 |R0603 	                            |1 	        |0603WAF1000T5E 	    |UniOhm         |
| 16 	|100K 	                 |R10 	                 |R0603 	                            |1 	        |0603WAF1003T5E 	    |UniOhm         |
| 17 	|49.9K 	                 |R11 	                 |R0603 	                            |1 	        |0603WAF4992T5E 	    |UniOhm         |
| 18 	|16.2K 	                 |R12 	                 |R0603 	                            |1 	        |0603WAF1622T5E 	    |UniOhm         |
| 19 	|ESP32-S 	             |U1 	                 |WIRELM-SMD_ESP32-S 	                |1 	        |ESP32-S 	            |Ai-Thinker     |
| 20 	|DB128V-5.0-2P-OG 	     |U3,U4,U5,U6 	         |CONN-TH_DB128V-5.0-2P-XX 	            |4 	        |DB128V-5.0-2P-OG 	    |DIBO           |
| 21 	|AP5100WG-7 	         |U7 	                 |SOT-23-6_L2.9-W1.6-P0.95-LS2.8-BR 	|1	        |AP5100WG-7	            |DIODES         |


Additionally a series of enclosures are designed for different use-cases.

![ESP32 Led Driver Case](/images/case-render.png "ESP32 Led Driver Case")

![ESP32 Led Driver](/images/photo.jpg "ESP32 Led Driver")