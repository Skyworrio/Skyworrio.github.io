---
title: Resume
hide:
  - navigation
  - toc
---

# Resume

<p class="lede">Electrical engineer focused on embedded hardware, power electronics, and controls.</p>

<!-- TODO: drop your resume PDF at docs/assets/Cade-Clonts-Resume.pdf, then uncomment the button below.
[:material-file-download-outline: Download PDF](assets/Cade-Clonts-Resume.pdf){ .md-button .md-button--primary }
-->

## Education

<div class="timeline" markdown>

<div class="timeline__item" markdown>
<div class="timeline__head"><h3>M.S., accelerated program</h3><span class="timeline__when">Expected Spring 2027</span></div>
<p class="timeline__org">Arizona State University</p>

- Graduate coursework: power electronic converters, applied photovoltaics, batteries and EV technologies, vehicle dynamics and control, multimodal ML for engineering applications
</div>

<div class="timeline__item" markdown>
<div class="timeline__head"><h3>B.S., Electrical Systems Engineering</h3><span class="timeline__when"><!-- TODO: graduation date --></span></div>
<p class="timeline__org">Arizona State University</p>

- Coursework projects include a custom ESP32 gateway board (EGR 314), digital filter design (EGR 334), electronic packaging cross-sections (EGR 394), and a two-semester industry capstone (EGR 401/402)
</div>

</div>

## Research

<div class="timeline" markdown>

<div class="timeline__item" markdown>
<div class="timeline__head"><h3>Undergraduate Researcher, 3DX Research Group</h3><span class="timeline__when">2025 – present</span></div>
<p class="timeline__org">Arizona State University, The Polytechnic School · Advisor: Dr. Dhruv Bhate</p>

- SURF / SCALE (DoD-supported) summer research fellow, 2026
- Designing, MSLA-printing, and flow-testing branching capillary networks (Murray's Law, da Vinci's rule, Hack's Law) for passive heat-pipe wicks ([details](projects/capillary-wicks/index.md))
- Selected the group's Elegoo Saturn 4 Ultra 16K MSLA printer against a $1,000 budget for sub-millimeter hair-like features
- Co-author, *Additive Manufacturing of Hair-like Materials: Design Principles, Process Constraints, and Manufacturing Strategies*, International Solid Freeform Fabrication Symposium, Austin, TX, August 2026
</div>

</div>

## Selected projects

<div class="timeline" markdown>

<div class="timeline__item" markdown>
<div class="timeline__head"><h3>ESP32 Wi-Fi / MQTT Gateway Board</h3><span class="timeline__when">Spring 2025</span></div>
<p class="timeline__org">ASU EGR 314 · 3-person team · Fulton Innovation Showcase</p>

- Designed the schematic, layout, BOM, firmware, and enclosure for an ESP32-S3 board with dual 3.3 V rails (AP62300 buck from 12 V, LDO from USB), sized from a 25 %-margin power budget
- Designed a fixed-length 64-byte framed UART protocol for a daisy-chained multi-board network with addressing, broadcast, and loop prevention
- Wrote async MicroPython firmware bridging the chain to an MQTT broker over mutually-authenticated TLS ([details](projects/wifi-mqtt-board/index.md))
</div>

</div>

## Skills

| Area | Tools and skills |
|---|---|
| **PCB and hardware** | Altium Designer, KiCad, SMT assembly and rework, board bring-up, power-rail design (buck, LDO), BOM and vendor sourcing |
| **Embedded firmware** | ESP32 (MicroPython, ESP-IDF), PIC (MPLAB/MCC), UART / I2C / SPI, MQTT over TLS, async event loops |
| **Power and energy** | Converter design and loss analysis, battery management, microgrid modeling (Xendee), PV system design |
| **Controls and modeling** | MATLAB / Simulink, digital filter design, vehicle dynamics simulation, ROS |
| **Fabrication** | FDM and MSLA 3D printing, CAD and enclosure design, sheet-metal fabrication |
