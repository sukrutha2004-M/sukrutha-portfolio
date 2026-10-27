# SUKRUTHA M — Embedded Systems Engineer Portfolio Website

A modern, high-performance, and responsive personal portfolio website engineered specifically for **SUKRUTHA M**, an **Embedded Systems Engineer**.

---

## 🌟 Highlights & Key Features

- **Dark Engineering Aesthetic:** Deep slate & obsidian theme with cyan, firmware emerald, and hardware amber accent lines inspired by printed circuit board (PCB) traces and microcontroller status indicators.
- **Interactive PCB Circuit Background:** Real-time HTML5 canvas rendering animated signal pulses traveling along orthogonal circuit traces that respond to mouse movement.
- **Hardware Telemetry Core Card:** Live system status display featuring target architectures (STM32, ESP32, AVR), active protocols, and pin signals.
- **Categorized Technical Skills:** Interactive category filtering for:
  - Programming (Embedded C, C, Python)
  - Microcontrollers (STM32, ESP32, MSP430, AVR ATmega32, PIC16F, LPC2148, Arduino Uno, Raspberry Pi Pico)
  - Development Tools (STM32CubeIDE, Keil µVision, MPLAB X IDE, Code Composer Studio, Arduino IDE)
  - Communication Protocols (UART, SPI, I2C)
  - Embedded Skills (GPIO, ADC, PWM, Motor Driver Interfacing, Breadboard Prototyping)
  - PCB Design (KiCad, Altium Designer)
  - Embedded Linux (Raspberry Pi GPIO, Basic Shell Scripting)
- **Interactive Project Simulators:**
  1. **PID Algorithm DC Motor Speed Control:** Interactive step-response oscilloscope with live sliders for $K_p$, $K_i$, $K_d$, dynamic curve calculation, overshoot %, settling time metrics, and preset tuning profiles.
  2. **Self-Balancing Boat Stabilization System:** Dynamic boat roll physics canvas with real-time FreeRTOS compensation, wave disturbance simulation, and stepper motor counter-torque tracking.
- **Comprehensive Project Modals:** Detailed architectural schematics, pinout tables, and firmware execution flows for both flagship projects.
- **Certification Section:** Prominent card detailing the **Certified Embedded Systems Engineer** credential from IPCS Global, Trivandrum (2025 – Present).
- **Education Timeline:** Clean visual chronology covering BSc in Instrumentation (NSS College, Nemmara), 12th (GHSS Peringottukurissi), and 10th (HSS Kuthanur).
- **Interactive Contact & Fast Actions:** One-click copy buttons for email & phone, functional message transmission simulation with toast alerts, and a direct download button for the resume PDF.
- **Fully Responsive & Accessible:** Optimized for desktop monitors, laptops, tablets, and smartphones with mobile drawer navigation.

---

## 📁 Project Directory Structure

```
sukrutha-portfolio/
├── index.html                           # Master semantic HTML5 page
├── README.md                            # Documentation & deployment guide
├── css/
│   └── style.css                        # Modern responsive CSS design system
├── js/
│   ├── circuit-canvas.js                # Interactive PCB background canvas animation
│   ├── simulations.js                   # Interactive PID & Boat stabilizer simulators
│   └── main.js                          # Sticky nav, modals, filters, and contact logic
└── assets/
    ├── resume.pdf                       # Downloadable resume PDF (placeholder)
    └── images/
        ├── profile-avatar.svg           # Embedded engineer silicon chip monogram
        ├── project-pid-placeholder.svg  # High-tech schematic for PID Motor Control
        └── project-boat-placeholder.svg # High-tech schematic for Boat Stabilization
```

---

## 🚀 How to Run Locally

You can open the website instantly with zero build steps or package managers required:

1. Double-click `index.html` in your file explorer, or
2. Right-click `index.html` and select **Open with > Chrome / Edge / Firefox**.

---

## 📄 How to Replace the Resume PDF

When you want to update your resume:
1. Save your resume PDF as `resume.pdf`.
2. Place it in the `assets/` directory (replacing `assets/resume.pdf`).
3. Both the navigation bar and hero "Download Resume" buttons will automatically download your updated PDF file.

---

## 🌐 Free 1-Click Hosting Options

- **GitHub Pages:** Create a repository named `<your-username>.github.io` or `portfolio`, push the files, and enable GitHub Pages in Settings.
- **Netlify / Vercel:** Drag and drop the `sukrutha-portfolio` folder directly into the Netlify/Vercel dashboard for an instant HTTPS URL.
