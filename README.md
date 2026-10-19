# ระบบควบคุมแบบศูนย์รวม

---

## 1. ระบบทดสอบเครื่องยนต์

### 1.1 MTU Series 538
* **Control:** 
  * Pneumatic Actuator
* **Monitoring:** 
  * Hardwired

### 1.2 MTU 16V 4000 M90
* **Control:** 
  * Modbus-TCP (ECU4)
* **Monitoring:** 
  * Modbus-TCP

### 1.3 PAXMAN 12VP185
* **Control:** 
  * Electric Actuator
* **Monitoring:** 
  * Hardwired

---

## 2. ระบบสนับสนุนการทดสอบ

### 2.1 ระบบน้ำระบายความร้อน

#### A. Cooling Tower
* **Control:** 
  * Pump & Fan Interlocked Control
  * Cooling Water Pumps
  * Make-up Water Supply
* **Monitoring:** 
  * System Status - Fan CT 6 EA
  * System Status - Pump 3 EA
  * System Status - Power supply
  * Temp - Hot/Cold
  * Reservoir Level
  * Pressure IN Dyno/Eng
* **Alarm:** 
  * Low Water level
  * High Temp - Water Basin
  * High Temp - Water In/Out

#### B. Primary Circuit (Stainless Steel Pipe)
* **Control:** 
  * Pump Coolant tank
  * Air Purge Control Valve
* **Monitoring:** 
  * System Status - Pump Control - Max/Min Temp
  * System Status - Thermal Dispersion Flow Switch
  * Pressure - in/out Eng.
  * Temp - in/out Heat Exchanger
  * Water level - Expansion Tank
* **Alarm:** 
  * High Temp - After Heat Exchanger
  * Low Pressure - before Heat Exchanger
  * Low Level - Expansion Tank

#### C. Secondary Circuit (HDPE)
* **Control:** 
  * Lube Oil Cooling Pump
  * Fresh water Cooling Pump
* **Monitoring:** 
  * Pressure - Raw water before Eng.
  * Pressure - Water in Dyno
* **Alarm:** 
  * Low Pressure - before Eng.
  * Low Pressure - in dyno

#### D. ระบบอุ่นน้ำ
* **Control:** 
  * Heater Coils 3 EA
  * Control Valves
* **Monitoring:** 
  * Water level - Coolant Tank
  * Pre-heating Temp
  * Temp - Coolant Tank
* **Alarm:** 
  * Low Coolant Level

---

### 2.2 ระบบอากาศอัด
* **Control:** 
  * Air Compressor - Remote Start/Stop
  * Reduce station - Remote Pressure Setpoint Adjustment
* **Monitoring:** 
  * System Status - Air Compressor
  * System Status - Valve Control
  * System Status - Power supply
  * System Status - Running Hours
  * Pressure - Air Start
  * Pressure - Air Control
  * Pressure - Air Receiver Tank
* **Alarm:** 
  * Low Pressure - Air Start
  * Low Pressure - Air Control
  * Low Pressure - Lube Oil
  * Condensate Drain Failure
  * Electrical Fault

---

### 2.3 ระบบน้ำมันหล่อ
* **Control:** 
  * Pump/Valve - Priming Loop
  * Pump/Valve - Fill
  * Pump/Valve - Drain
* **Monitoring:** 
  * System Status - Pump Control - Max/Min Temp
  * System Status - Thermal Dispersion Flow Switch
  * Pressure - in/out Eng.
  * Temp - in/out Heat Exchanger
* **Alarm:** 
  * High Temp - After Heat Exchanger
  * Low Pressure - before Heat Exchanger

---

### 2.4 ระบบน้ำมันเชื้อเพลิง

#### A. Fuel Transfer System
* **Control:** 
  * Fuel Transfer Pump
* **Monitoring:** 
  * Pump Status
  * Storage Tank Level & Volume
* **Alarm:** 
  * Low Storage Tank Level

#### B. Fuel Service System
* **Control:** 
  * Fuel Chiller System
  * Fuel Metering System
* **Monitoring:** 
  * System Status - Transfer Pump Status
  * System Status - Fuel Chiller Status
  * Day Tank Level/Volume
  * Fuel Temp - In/Out Eng.
  * Fuel Pressure - In/Out Eng.
  * Fuel Consumption Rate
* **Alarm:** 
  * Low Day Tank Level
  * High Fuel Temp
  * Low Fuel Pressure

---

### 2.5 ระบบท่อแก๊สเสีย
* **Monitoring:** 
  * Exhaust Parameters - Back Pressure
  * Exhaust Parameters - Total Exhaust Temp
* **Alarm:** 
  * High Exhaust Temp
