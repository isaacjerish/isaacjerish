<h2 align="center">👋🏼 Isaac Jerish — bare-metal code ➜ silicon</h2>
<p align="center">
  3rd-year <strong>Computer Engineering</strong> @ Georgia Tech &nbsp;|&nbsp;
  Embedded Systems & VLSI
</p>

---

### ⚡ What I’m hacking on
- 🔌 **Modular Sensor Hub** — STM32 runs FreeRTOS; gathers temperature, pressure, and IMU data over **I²C**, packages it, and streams telemetry via **UART** to a desktop dashboard. 100 Hz end-to-end, built with **CMake** for portable builds.  
- 🚁 **CAN-Based Drone Telemetry Unit** — ESP32 monitors ESC currents & battery voltage, aggregates over **CAN** bus, pushes live data to a Raspberry Pi ground station over Wi-Fi; written in C++17 with RTOS tasks.  
- 🌐 **Ethernet Remote Oscilloscope** — Mbed board samples two analog channels, buffers with DMA, and serves waveform JSON over **Ethernet** so any browser can render live signals (FFT coming next).

<details>
<summary>💡 First open-source targets (next sprint)</summary>

| Stack | First easy PR |
|-------|---------------|
| **Zephyr RTOS** | Clarify DHT22 timing in `sensors` docs |
| **tinyUSB** | Fix typo + add PID entry for STM32F411-Nucleo |
| **rust-embedded/hal** | Merge MCP3008 ADC example into `stm32f4xx-hal` |
</details>

### 🧰 Toolbox
**Programming Languages**   `C/C++` · `Python` · `Java` · `Verilog/VHDL` · `RISC-V asm` · `MATLAB`  
**Tools & Frameworks**   `Embedded Linux` · `Arduino/Mbed/ESP32` · `STM32` · `Raspberry Pi` · `Git` · `Multimeter` · `Oscilloscope`  
**Protocols & Technologies**   `FreeRTOS` · `CAN` · `I²C` · `UART` · `SPI` · `PWM` · `Ethernet`  
**Personal**   Problem-Solving · Debugging · Technical Communication · Adaptability

### 🔗 Recent upstream activity
> ⚠️ First contribution in review — watch this space!

<p align="center">
  <!--<img src="assets/demo.gif" width="480" alt="Project demo placeholder"/> -->
</p>

### 📫 Reach me
`ijersh6@gatech.edu` • [LinkedIn](https://linkedin.com/in/isaacjerish)