# 📡 Sensors and Technology

## 🔍 Sensors Used
- Heart Rate Sensor: Measures heartbeat.
- GSR Sensor (Galvanic Skin Response): Measures skin conductivity (stress level).
- Accelerometer: Detects sudden movement.

---

## 💡 Why these sensors?
- Physical stress signals appear before behavioral signs.
- Objective, real-time, non-invasive monitoring.

---

## 🛠️ Simple Example:
Using Arduino:
1. Connect a heart rate sensor.
2. Turn on an LED if the heart rate exceeds 120 bpm.

```cpp
if (heartRate > 120) {
    digitalWrite(ledPin, HIGH);
}
