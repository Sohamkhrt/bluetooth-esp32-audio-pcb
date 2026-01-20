# bluetooth-esp32-audio-pcb
A custom Bluetooth Audio PCB for motorcycle helmets, powered by ESP32 and PCM5102A with integrated LiPo BMS and power management
<img width="1723" height="892" alt="raytracingpcbaudio" src="https://github.com/user-attachments/assets/043ff62c-2e4e-40b0-881a-15b3d5623d08" />
<img width="1723" height="892" alt="raytracingpcbaudio2" src="https://github.com/user-attachments/assets/dbd4f580-cde7-46ef-9a51-8b9bb3ad14f8" />
<img width="1009" height="716" alt="Screenshot 2026-01-20 182242" src="https://github.com/user-attachments/assets/a4865c93-3dbd-4628-9142-536b2e9f23aa" />
<img width="828" height="695" alt="Screenshot 2026-01-20 182341" src="https://github.com/user-attachments/assets/eae276d3-5b55-4a3b-aa07-93ca4b724ae2" />
<img width="1147" height="823" alt="Screenshot 2026-01-20 182503" src="https://github.com/user-attachments/assets/4d3e89dd-77a1-4eab-8bc0-98714ef6069d" />
Project Highlights

Core Logic: ESP32-WROOM-32 for Bluetooth A2DP audio streaming.

Audio: High-fidelity I2S interface using the PCM5102A DAC (32-bit/384kHz capable).

Power Management: Integrated TP4056 LiPo charger with DW01A protection circuitry (Over-charge/Over-discharge/Short-circuit protection).

Regulation: Low-dropout (LDO) 3.3V regulation (AP2112K) with stable capacitor banking for RF noise suppression.

Technical Challenges Solved

MOSFET Matching: Resolved a critical pinout mismatch between standard TSSOP-8 and SOT-23-6 dual N-channel MOSFETs for battery protection.

Signal Integrity: Implemented dedicated ground planes (copper pours) on both layers with stitching vias to minimize EMI and ground loops for clear audio.

Space Constraint: Designed within a tight 50mm x 50mm form factor to fit inside a helmet cheek pad.

EDA Tool Used: KiCad 9.0
