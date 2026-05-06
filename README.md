# ESP32 CAN Bus RPM Sensor

Proyek IoT buat baca RPM kipas DC pake sensor FC-51, dikirim lewat protokol CAN Bus MCP2515 ke Node-RED.

**Demo Video**: 

### Hardware yang Dipake
- ESP32 DevKit V1
- MCP2515 CAN Module  
- FC-51 Infrared Sensor
- Motor DC + Kipas 12V

### Fitur Utama
1. Baca RPM real-time pake interrupt
2. Kirim data via CAN Bus ID 0x100
3. Monitor di Node-RED Dashboard
4. Filter data pake moving average

### Skill yang Dipake
`ESP32` `CAN Bus` `C++` `MCP2515` `Arduino IDE` `Node-RED` `IoT`

### Wiring Diagram
