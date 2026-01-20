# Prototype IoT Power Meter

A smart IoT-enabled power meter prototype built for **real-time monitoring** and remote telemetry of electrical parameters.  
The system integrates a **PZEM-04T power meter** with voltage and current transformers, interfaced to an **STM32H743 Nucleo board**. Communication is handled via the **onboard Ethernet PHY**, connecting to a 4G router, with the **Mongoose TCP/IP stack** managing **MQTT and WebSocket protocols**. The front-end, developed in **React**, displays real-time energy parameters including voltage, current, power factor, and energy consumption. This design allows scalable **networked energy monitoring** for residential and industrial applications.

---

## System Overview

- **Voltage & Current Measurement:** PZEM-04T power meter with CT/PT for accurate energy measurement.  
- **Microcontroller:** STM32H743 Nucleo board for deterministic data aggregation and control.  
- **Communication:** Ethernet PHY connected to a LAN port of a 4G router.  
- **Protocols:** Mongoose TCP/IP stack for **MQTT** and **WebSocket** communication.  
- **Front-end:** React-based dashboard displaying voltage, current, power factor, and energy in real-time.  
- **Deployment:** Scalable prototype for IoT energy monitoring applications.

---

## Key Features

- Real-time measurement of voltage, current, power factor, and energy.  
- **STM32H743 MCU** for reliable control and data handling.  
- Ethernet-based communication with **MQTT and WebSocket** support.  
- **React dashboard** for live parameter visualization.  
- LAN-connected via 4G router for remote telemetry.  
- Prototype suitable for residential or industrial IoT energy monitoring.

---

## Hardware Components

- **PZEM-04T** – Energy meter module with CT/PT support.  
- **STM32H743 Nucleo board** – High-performance MCU for real-time processing.  
- **Ethernet PHY** – Onboard Ethernet interface for LAN connectivity.  
- **Voltage & Current Transformers** – For accurate measurement of mains energy.

---

## Communication & Connectivity

- **Ethernet** connection to LAN port of 4G router.  
- **MQTT** for cloud-ready telemetry.  
- **WebSocket** for real-time dashboard updates.  
- Scalable for networked deployment of multiple meters.

---

## Use Cases

- Real-time residential or commercial energy monitoring.  
- IoT-based smart grids or microgrid projects.  
- Remote telemetry and energy data collection.  
- Front-end dashboards for visualization of energy parameters.

---

## Author

**Toyyib Olalekan Akinkunmi**  
Embedded Systems & IoT Engineer

---

## License

This project is proprietary / for portfolio demonstration purposes.
