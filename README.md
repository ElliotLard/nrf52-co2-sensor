# nrf52-co2-sensor

![MCU](https://img.shields.io/badge/MCU-nRF52840-blue)
![Sensor](https://img.shields.io/badge/Sensor-SCD30-green)
![Interface](https://img.shields.io/badge/Interface-BLE%20%2B%20I2C-lightgrey)

BLE-based smart home compatible CO₂ sensor built around the **nRF52840 (via MDBT50Q module)** and the **Sensirion SCD30 NDIR CO₂ sensor**.

The device measures indoor CO₂ concentration and transmits readings wirelessly using **Bluetooth Low Energy (BLE)** for integration with smart home systems or mobile applications.

This project includes:

- Custom **schematic design**
- **PCB layout** in KiCad
- **BLE communication**
- Sensor integration using **I²C**

---

# Project Status

**Current Status (30 July 2026)**
- Rev A Board has been printed and assembled
---
#Front
<img width="3189" height="1901" alt="IMG_5199" src="https://github.com/user-attachments/assets/e0a3ebb4-8903-462f-8f5d-5eceb88e8438" />

#Back
<img width="3924" height="2136" alt="IMG_5160" src="https://github.com/user-attachments/assets/ac1d5edb-9903-43e0-aba9-ae04c07e93ec" />


# Hardware Design

## Schematic (Rev A)

<img width="1019" height="643" alt="image" src="https://github.com/user-attachments/assets/8754bd1f-20a0-4323-b7d6-042973b2565d" />

## PCB Layout (Rev A)

<img width="734" height="355" alt="image" src="https://github.com/user-attachments/assets/21d132f4-f084-4601-bfa1-aca9cad92252" />

---

# Design Goals

- Accurate CO₂ measurement
- Wireless communication via **Bluetooth Low Energy**
- USB-C powered device
- Smart home compatibility

---

# Major Components

## MCU + BLE

**MDBT50Q-1MV2**  
Contains **Nordic nRF52840 BLE microcontroller**

<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/f8f17d42-470f-4c44-9b13-8ff0c55e9da5" />

---

## CO₂ Sensor

**Sensirion SCD30**

NDIR-based CO₂ sensor with integrated temperature and humidity measurement.

<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/69c71071-2cbf-4c6e-bca0-c45bb98f0f6d" />

---

## USB-C Receptacle

**USB4105-GF-A**

Used for power and optional USB communication/debugging.

<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/4cef42a2-7a26-43f2-bd7c-1c12c8ec1a92" />

---


<!---
Future updates:

- Rev B schematic
- PCB layout screenshots
- Fabricated board photos

---
-->
# Firmware

*(Placeholder — firmware development will begin after PCB assembly)*

Planned features:

- I²C communication with SCD30
- CO₂ measurement acquisition
- BLE data transmission
- Low power operation

---

# Tools Used

- **KiCad** — schematic and PCB design
- **Git / GitHub** — version control
- **Datasheets and reference designs** from component manufacturers

---

# Future Work

- BLE data integration with **Home Assistant**
- Explore possibility of Battery-powered variant
- Compact enclosure design
- Airflow optimization for accurate sensing

---

<!---
# License

*(Placeholder — consider adding MIT or Apache license)*
-->
