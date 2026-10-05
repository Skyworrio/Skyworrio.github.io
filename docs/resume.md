---
title: Resume
hide:
  - navigation
  - toc
---

# Resume

<p class="lede">Electrical engineering graduate (Magna Cum Laude) in ASU's accelerated M.S. program, focused on embedded hardware and microelectronics. U.S. citizen, eligible for a DoD security clearance, and open to relocation.</p>

[:material-file-download-outline: Download PDF](assets/Cade-Clonts-Resume.pdf){ .md-button .md-button--primary }
[:fontawesome-brands-linkedin: LinkedIn](https://www.linkedin.com/in/cadeclonts){ .md-button }
[:fontawesome-solid-envelope: caclonts@gmail.com](mailto:caclonts@gmail.com){ .md-button }

## Education

<div class="timeline" markdown>

<div class="timeline__item" markdown>
<div class="timeline__head"><h3>M.S., Engineering (Accelerated Master's)</h3><span class="timeline__when">Expected Spring 2027</span></div>
<p class="timeline__org">Arizona State University · Mesa, AZ</p>

- Graduate coursework: Power Electronic Converters &amp; Systems, Engineering Analysis I, Multimodal LLMs for Engineering Applications
</div>

<div class="timeline__item" markdown>
<div class="timeline__head"><h3>B.S.E., Engineering (Electrical Systems)</h3><span class="timeline__when">May 2026</span></div>
<p class="timeline__org">Arizona State University · Mesa, AZ</p>

- GPA 3.62 · Magna Cum Laude · Dean's List (4 terms)
- Relevant coursework: Heterogeneous Integration &amp; Electronic Packaging, Analog-Digital Interface, Principles of Modern Electromagnetism, Embedded Systems Design I &amp; II, Principles of Systems Engineering (graduate)
</div>

</div>

## Experience

<div class="timeline" markdown>

<div class="timeline__item" markdown>
<div class="timeline__head"><h3>Student Researcher, 3DX Research Group (SCALE)</h3><span class="timeline__when">Nov 2023 – Present</span></div>
<p class="timeline__org">Arizona State University · Advisor: Dr. Dhruv Bhate</p>

- Lead a study of 3D-printed branching capillary channels for electronics cooling, testing Murray's, da Vinci's, and Hack's laws ([details](projects/capillary-wicks/index.md))
- Selected the group's high-resolution MSLA printer (Elegoo Saturn 4 Ultra 16K) within a $1,000 budget for hair-like structures
- Compiled the additive manufacturing process comparison for a co-authored SFF 2026 conference paper
</div>

<div class="timeline__item" markdown>
<div class="timeline__head"><h3>East Valley Industrial Products (part-time)</h3><span class="timeline__when">Aug 2020 – Present</span></div>

- Fabricate diamond-plate steel water box lids: plasma-cut ~12 blanks per 4×8 ft sheet, bend lips, weld ribs
- Cross-trained across the full production process; currently responsible for finishing and painting
</div>

<div class="timeline__item" markdown>
<div class="timeline__head"><h3>Case IH, Goodman AG</h3><span class="timeline__when">Nov 2020 – Jan 2023</span></div>

- Installed, calibrated, and repaired GPS autopilot systems on farm tractors
- Diagnosed and resolved autopilot faults on-site, minimizing downtime for growers
</div>

</div>

## Academic projects

<div class="timeline" markdown>

<div class="timeline__item" markdown>
<div class="timeline__head"><h3>ESP32 Wi-Fi / MQTT Gateway PCB</h3><span class="timeline__when">EGR 314 · Spring 2025</span></div>

- Designed a custom ESP32-S3 board in Altium as the Wi-Fi gateway for a networked multi-board system, using trade studies to select the MCU and regulator
- Defined a 64-byte framed UART protocol with addressing, broadcast, and forwarding; wrote async MicroPython firmware publishing sensor data over MQTT with TLS mutual authentication
- Designed dual power inputs (12 V synchronous buck, 5 V USB LDO) from a load budget with 25% margin; demoed end to end at the Fulton Schools Innovation Showcase ([details](projects/wifi-mqtt-board/index.md))
</div>

<div class="timeline__item" markdown>
<div class="timeline__head"><h3>Digital Filter Design</h3><span class="timeline__when">EGR 334 · Fall 2025</span></div>

- Designed a Butterworth IIR digital filter in MATLAB and analyzed its magnitude and phase response
- Compared it against the team's Chebyshev design, weighing Butterworth's flat passband against Chebyshev's steeper roll-off
</div>

<div class="timeline__item" markdown>
<div class="timeline__head"><h3>ROS Computer Vision Color-Tracking Robot</h3><span class="timeline__when">EGR 530 · Spring 2026</span></div>

- Built a computer vision application in ROS on a ROSMASTER X3 mobile robot that detects a target by color in the onboard camera feed and drives the robot to follow it ([details](projects/ros-tracking/index.md))
</div>

</div>

## Technical skills

| Area | Tools and skills |
|---|---|
| **Hardware** | Altium, KiCad, PCB bring-up, SMT soldering, buck/LDO rail design, oscilloscope, DMM |
| **Embedded &amp; software** | C, Python, MicroPython, MATLAB, ROS, ESP32, PSoC, UART, I²C, PWM, ADC, MQTT/TLS |
| **Microelectronics &amp; fab** | SEM, chip cross-sectioning and polishing, MSLA/FDM 3D printing, AutoCAD, welding |

## Publications

I. Chavez Martinez, C. Yuen, **C. Clonts**, Z. Okun, A. Sarrasin, A. Potts, M. Nunez, A. Nizamudeen, R. Duong, H. Emady, C. Ozturk, D. Bhate, "Additive Manufacturing of Hair-like Materials: Design Principles, Process Constraints, and Manufacturing Strategies," accepted for publication in *Proceedings of the 37th Annual International Solid Freeform Fabrication Symposium*, Austin, TX, Aug. 3–5, 2026.
