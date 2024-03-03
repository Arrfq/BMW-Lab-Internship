# USRP B210
---
![image](https://hackmd.io/_uploads/rkzrB0Zaa.png)
![USRP_B210-obl-1000__99357](https://hackmd.io/_uploads/ByzkHRW6p.png)

What is USRP B210?
---
The USRP B210 is a fully integrated, single-board Universal Software Radio Peripheral (USRP™) platform designed for low-cost experimentation. It offers continuous frequency coverage from 70 MHz to 6 GHz and features a direct conversion transceiver providing up to 56 MHz of real-time bandwidth. This device combines an open and reprogrammable Spartan-6 FPGA, fast SuperSpeed USB 3.0 connectivity, and full support for the USRP Hardware Driver (UHD) software, enabling immediate development with GNU Radio and other applications like OpenBTS. The USRP B210 allows users to prototype various applications such as FM and TV broadcast, cellular, GPS, WiFi, and more. It supports coherent MIMO capability and provides a benchmarked real-time throughput of 61.44MS/s quadrature. The device is accessible through the UHD API, supporting both C/C++ and Python programming languages. Additionally, it offers compatibility with graphical programming tools like GNU Radio and industry-standard development environments such as RFNoC, LabVIEW, and MATLAB/Simulink.

B210 Architecture
---
The integrated RF frontend on the USRP B210 is designed with the new Analog Devices AD9361, a single-chip direct-conversion transceiver, capable of streaming up to 56 MHz of real-time RF bandwidth. The B210 uses both signal chains of the AD9361, providing coherent MIMO capability. Onboard signal processing and control of the AD9361 is performed by a Spartan-6 XC6SLX150 FPGA connected to a host PC using SuperSpeed USB 3.0. The USRP B210 real time throughput is benchmarked at 61.44MS/s quadrature, providing the full 56 MHz of instantaneous RF bandwidth to the host PC for additional processing using GNU Radio or applications that use the UHD API. For detailed throughput capabilities in various SISO and MIMO configurations, please see the USRP B200/B210 Benchmark Table.

Key Details
---
The USRP B210 is a 2x2 MIMO (Multiple Input, Multiple Output) software-defined radio (SDR). Here are some key details about the USRP B210:
- Frequency Coverage: The USRP B210 provides continuous frequency coverage from 70 MHz to 6 GHz1.
- Bandwidth: It offers a bandwidth of 56 MHz1.
- Channels: The B210 has two receive and two transmit channels, allowing for flexible communication and experimentation.
- Applications: The USRP B210 is commonly used for various applications, including wireless communication research, cognitive radio, signal processing, and software-defined radio development.
- Architecture: It features a larger FPGA (Field-Programmable Gate Array) and includes GPIO (General Purpose Input/Output) pins for additional flexibility.
- Power Supply: The B210 can be powered via USB 3.0 and includes an external power supply.

---
**FEATURES**

- RF coverage from 70MHz to 6GHz range
- 2 transmit (TX) and 2 receive (RX) channels, Half or Full Duplex
- Fully coherent 2 x 2 MIMO capability
- Xilinx Spartan 6 XC6SLX150 FPGA
- Instantaneous bandwidth:
- Up to 56MHz in 1 x 1
- Up to 30.72MHz in 2 x 2
- More than 10dBm power output
- Less than 8dB receive noise figure
- 10MHz clock reference
- Flexible rate 12-bit ADC/DAC
- 61.44MS/s (maximum) ADC/DAC sample rate
- Includes 6V DC power supply
- USB 3.0 SuperSpeed interface
- Standard-B USB 3.0 connector
- Supports USRP hardware driver 3.9.2 (or later)
- Supports GNU Radio, C++, and Python APIs
- GPIO capability
- 0°C to 45°C operating temperature range
- 97mm x 155mm x 15mm dimensions
- Weighs about 350g
- Grounded mounting holes

---
![Screenshot 2024-03-03 at 17.12.26](https://hackmd.io/_uploads/rJsXRpWTT.png)


---
Source
---
[B200/B210/B200mini/B205mini Getting Started Guides](https://kb.ettus.com/B200/B210/B200mini/B205mini_Getting_Started_Guides)
[Digilent Ettus USRP™ B210](https://eu.mouser.com/new/digilent/digilent-ettus-usrp-b210/?_gl=1*10qazc*_ga*MTQ5MDA3ODQyNy4xNzA5NDYwNjcy*_ga_15W4STQT4T*MTcwOTQ2MDY3Mi4xLjAuMTcwOTQ2MDY5OC4zNC4wLjA.*_ga_1KQLCYKRX3*MTcwOTQ2MDY3Mi4xLjAuMTcwOTQ2MDY5OC4wLjAuMA..)
[About Ettus USRP B210](https://www.ettus.com/announcing-the-usrp-b200-and-usrp-b210/)
[Ettus USRP B210 In Shop](https://digilent.com/shop/ettus-usrp-b210-2x2-70mhz-6ghz-sdr-cognitive-radio/)

