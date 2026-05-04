<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=760&lines=FPGA+%2F+SoC+Verification+%26+Emulation+Engineer;SystemVerilog+%7C+UVM+%7C+RTL+Design+%7C+FPGA;Protocol+VIP+Development+%7C+Hardware+Demos" alt="Typing SVG" />
  </a>
</p>


As a digital design and verification/emulation engineer focused on **ASIC accelerated verification & emulation**, **protocol VIP development**, and **FPGA-based RTL design**.

My day-to-day work is around reusable UVM environments, protocol verification, RTL debug, and hardware bring-up flows.  
This GitHub is where I keep my personal projects structured, documented, and runnable.

---

## Areas of Focus

### Verification & Emulation

SystemVerilog · UVM · Protocol VIPs · Scoreboarding · Functional Coverage · Assertions · Palladium · Xcelium

### RTL & FPGA

RTL Design · FPGA Design Flows · Verilog · SystemVerilog · Gowin · Vivado · ModelSim · Questa · Timing Closure

### Embedded / MCU

STM32 / Cortex-M4 · TI Stellaris · PIC · Bare metal programming  
UART · SPI · I2C · ADC · PWM

### Tools & Scripting

TCL · Python · C · Makefile · Simulation scripts · Shell Scripting · FPGA build automation

---

## Tech Stack

![SystemVerilog](https://img.shields.io/badge/SystemVerilog-blue?style=flat-square)
![UVM](https://img.shields.io/badge/UVM-4A90D9?style=flat-square)
![FPGA](https://img.shields.io/badge/FPGA-blueviolet?style=flat-square)
![Gowin](https://img.shields.io/badge/Gowin-FPGA-orange?style=flat-square)
![Verilog](https://img.shields.io/badge/Verilog-555555?style=flat-square)
![TCL](https://img.shields.io/badge/TCL-orange?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square)
![Vivado](https://img.shields.io/badge/Vivado-FF0000?style=flat-square)

---

## Project Portfolio

### RV32I Design & UVM TB

| Project | Description |
| --- | --- |
| [rv32i_axi4l_subsystem_uvm_tb](https://github.com/ayengec/rv32i_axi4l_subsystem_uvm_tb) | Self-checking UVM testbench for an RV32I AXI4-Lite CPU subsystem with reference model, scoreboard, and coverage |

### Verification & VIP

| Project | Description |
| --- | --- |
| [AXI4_Lite_VIP](https://github.com/ayengec/AXI4_Lite_VIP) | UVM-based AXI4-Lite master VIP with example DUT, tests, logs, and waveform support |
| [APB3_VIP](https://github.com/ayengec/APB3_VIP) | UVM-based APB3 master VIP with structured components and runnable scripts |
| [SPI_VIP](https://github.com/ayengec/SPI_VIP) | Reusable SPI verification environment supporting all 4 CPOL×CPHA modes |
| [I2C_VIP](https://github.com/ayengec/I2C_VIP) | I2C protocol VIP with configurable driver, monitor, sequencer, and scoreboard |
| [UART_VIP](https://github.com/ayengec/UART_VIP) | UART verification IP focused on clean, reusable testbench architecture |
| [DHT22_VIP](https://github.com/ayengec/DHT22_VIP) | UVM VIP for the DHT22 one-wire sensor protocol with CRC checking, error injection, and regression support |

### Gowin FPGA Projects

Main repository: [Gowin_FPGA_Design_Projects](https://github.com/ayengec/Gowin_FPGA_Design_Projects)

| Project | Description |
| --- | --- |
| [ddr3_test_w_UART_menu](https://github.com/ayengec/Gowin_FPGA_Design_Projects/tree/main/ddr3_test_w_UART_menu) | DDR3 test design with a UART-based interactive menu for real board bring-up |
| [hdmi_ayengec_demo](https://github.com/ayengec/Gowin_FPGA_Design_Projects/tree/main/hdmi_ayengec_demo) | HDMI output demo for the Gowin / Tang Primer FPGA platform |
| [macos_i2c_rtc_uart](https://github.com/ayengec/Gowin_FPGA_Design_Projects/tree/main/macos_i2c_rtc_uart) | I2C RTC interface with UART output on Gowin FPGA |
| [macos_lcd_spi_and_dht22](https://github.com/ayengec/Gowin_FPGA_Design_Projects/tree/main/macos_lcd_spi_and_dht22) | SPI TFT display with One-Wire DHT22 temperature and humidity monitoring on Gowin FPGA |
| [macos_led_knight_rider](https://github.com/ayengec/Gowin_FPGA_Design_Projects/tree/main/macos_led_knight_rider) | macOS-friendly Gowin FPGA workflow demo with LED chaser / Knight Rider effect |
| [macos_rgb_led_w_button_ws2812](https://github.com/ayengec/Gowin_FPGA_Design_Projects/tree/main/macos_rgb_led_w_button_ws2812) | WS2812 RGB LED controller with push-button based color and brightness control |

### FPGA / RTL

| Project | Description |
| --- | --- |
| [FPGA-Design-with-Systemverilog](https://github.com/ayengec/FPGA-Design-with-Systemverilog) | RTL-oriented SystemVerilog design examples and FPGA projects |
| [Bresenham_Line_VGA_BASYS3](https://github.com/ayengec/Bresenham_Line_Algorithm_VGA__BASYS3) | Bresenham's line algorithm implemented on BASYS3 via VGA output |
| [TCL_for_RTL](https://github.com/ayengec/TCL_for_RTL) | TCL scripting notes and examples for RTL and FPGA design workflows |

### Embedded / MCU

| Project | Description |
| --- | --- |
| [STM32F4_Projects](https://github.com/ayengec/STM32F4_Projects) | Low-level peripheral programming on STM32F4 / Cortex-M4 |
| [Stellaris_LM4F120XL_Projects](https://github.com/ayengec/Stellaris_LM4F120XL_Projects) | Peripheral-level embedded projects for TI Stellaris LaunchPad |
| [PIC_microcontroller_projects](https://github.com/ayengec/PIC_microcontroller_projects) | PIC-based projects covering UART, ADC, PWM, I2C, and SPI |

---

## Current Direction

I am currently building more public examples around:

- FPGA board bring-up
- Gowin/Tang Primer development
- DDR3, UART, HDMI, and display-oriented FPGA projects
- Reusable UVM VIPs for common protocols
- Practical RTL verification flows with scripts, logs, and waveform references

---

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alican-yenge%C3%A7-24b58680)
