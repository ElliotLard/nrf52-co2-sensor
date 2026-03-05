# nrf52-co2-sensor

#Description:
BLE-based CO2 sensor using nRF52(via MDBT50Q) and SCD30. Device is intended to allow smart home compatible air quality/CO2 detection.

Current State of project as of 03/05/25:
Rev A of Schematic is getting some final adjustments, then I will just need to finalize footprints for all components before moving on to PCB layout.

Major Components Utilized:
MCU + BLE: MDBT50Q-1MV2 (contains nRF52840)
<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/f8f17d42-470f-4c44-9b13-8ff0c55e9da5" />

CO2 Sensor: SCD30
<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/69c71071-2cbf-4c6e-bca0-c45bb98f0f6d" />

LDO 5V -> 3.3V: TLV75533PDBVR
<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/1e76d243-6e61-4710-bae9-95faf6b0d0c5" />

USB C receptacle for power and data: USB4105-GF-A
<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/4cef42a2-7a26-43f2-bd7c-1c12c8ec1a92" />

# Schematic as of 03/05/25
<img width="1019" height="643" alt="image" src="https://github.com/user-attachments/assets/8754bd1f-20a0-4323-b7d6-042973b2565d" />
