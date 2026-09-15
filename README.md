# vital-signs-early-warning
A low-cost wearable that monitors patients' vital signs in real time and alerts nurses before deterioration becomes critical bringing early-warning intelligence to understaffed hospital wards using affordable, locally available sensors.
Problem
In Egypt's public and many private hospitals, nurse-to-patient ratios are often too low for continuous manual monitoring, especially overnight or in overcrowded wards. Critical patient deterioration is frequently caught late, when intervention is harder and outcomes are worse.
Solution
A wristband device tracks:
	•	Heart rate & SpO2 (blood oxygen)
	•	Body temperature
Readings feed into a lightweight early-warning scoring model (inspired by clinical scores such as MEWS/NEWS), which flags at-risk patients on a real-time nurse-facing dashboard — before vitals become critical.
Tech Stack
Hardware
	•	ESP32 microcontroller
	•	MAX30102 (heart rate & SpO2 sensor)
	•	Digital temperature sensor (e.g. DHT22)
	•	Wristband form factor
Software
	•	Firmware: Arduino/ESP-IDF (C++)
	•	Backend: real-time data ingestion + scoring model
	•	Frontend: nurse dashboard with live readings and color-coded alerts
