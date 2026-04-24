FPGA MM:SS Counter（60进制分秒计数器）

Project Overview
This project implements a 60-based minute-second (MM:SS) counter on FPGA using Quartus II.  
The system counts from **00:00 to 59:59** and displays the result on a 7-segment display.

---

Platform
- FPGA Board: DE1 Cyclone II
- Software: Quartus II 13.0
- Design Method: AHDL + Block Diagram (BDF)

Features
- Counts from 00:00 to 59:59 (MM:SS format)
- Supports both up-counting and down-counting modes
- Implements modulo-60 counting for seconds and minutes
- Automatic carry and borrow between seconds and minutes
- Displays output on 7-segment displays
- Supports partial reset (reset seconds or minutes independently)
- Supports global reset (reset entire system to 00:00)
- Designed using AHDL and schematic-based methodology

- I finished it with 1h22min！ 你也来试试吧！
