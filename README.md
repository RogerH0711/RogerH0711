## Hi, I'm Roger

CS undergrad at National Cheng Kung University, Tainan. I build things that sit close to the hardware — firmware, sensors, and the signal processing that turns a noisy measurement into a number you can actually trust.

Mostly Swift, C and Python. I care about being able to *prove* a result is right, not just watch it run.

---

### Projects

**[TurntableRPM](https://github.com/RogerH0711/TurntableRPM)** — Measures a turntable's speed and wow & flutter to 0.1% using nothing but an iPhone's gyroscope.

The algorithm core is plain Swift with no UIKit or CoreMotion dependency, so its 97 tests run natively on macOS and in a Linux container — which is what makes CI meaningful when the Simulator has no gyroscope. Golden values come from an independent Python implementation rather than Swift's own output, so changing the maths means changing it twice and proving both agree.

`Swift` `CoreMotion` `SwiftUI` `XcodeGen` `GitHub Actions`

**[STM32-ultrasonic-radar](https://github.com/RogerH0711/STM32-ultrasonic-radar)** — An ultrasonic radar built on an STM32F103C8T6.

Firmware sweeps an SG90 servo, median-filters HC-SR04 distance readings, and streams CSV over UART at 115200 baud while accepting manual angle commands. A Python desktop app renders the live polar view and switches between automatic and manual control.

`C` `STM32 HAL` `CubeMX` `UART` `Python`

**[Hexapod-ROS2-Controller](https://github.com/RogerH0711/Hexapod-ROS2-Controller)** — A 12-DOF hexapod robot. First place in NCKU's Intro to Digital Circuit Design final project.

Six-person team. I led the project and owned the ROS 2 environment and the end-to-end hardware/software integration; the tripod gait algorithm was written by two teammates, credited in the repo.

`ROS 2` `Python` `ESP32` `serial bus servos`

---

### Currently

Learning Verilog and digital design — working through HDLBits.

📫 f74146115@gs.ncku.edu.tw
