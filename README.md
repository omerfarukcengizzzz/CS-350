# CS-350 Final Portfolio – Omer Cengiz

This portfolio showcases two projects I worked on during CS-350 that reflect what I’ve learned about embedded systems, GPIO control, state machines, and real-time input/output on the Raspberry Pi.

---

## 🔴 Morse Code Milestone (Module 5)

**Project Summary:**  
This project transmits messages in Morse code using GPIO LEDs and a button. Pressing the button toggles the message between “SOS” and “OK.” I used a state machine to control timing, blinking patterns, and LCD message updates.

**Skills Demonstrated:**
- GPIO control with LED lights
- State machine implementation
- Multithreading for non-blocking input
- LCD message display
- Button input handling with GPIO interrupts

**Reflection:**  
This was my favorite milestone. It challenged me to coordinate hardware timing while staying responsive to button presses. I really learned the value of clean state transitions and how multithreading can make embedded systems more responsive.

📂 [View Morse Code Project Files](./Morse%20Code%20Milestone%20%28Module%205%29)

---

## 🌡️ Smart Thermostat Lab (Module 7)

**Project Summary:**  
A full thermostat prototype using real sensor data, button controls, LED indicators for heat/cool modes, and serial output. The state machine handles three modes: heat, cool, and off, while sending updates over UART.

**Skills Demonstrated:**
- Real-time temperature monitoring (I2C sensor)
- UART serial communication
- State machine with dynamic logic
- PWM LED fading
- Multi-threaded display updates on LCD

**Reflection:**  
This project brought everything together. I was able to integrate sensors, user input, display output, and serial communication into one working system. It really felt like a full IoT device.

📂 [View Thermostat Project Files](./Thermostat%20Lab%20%28Module%207%29)

---

## 🧠 Course Reflection

This course helped me get more comfortable designing embedded systems from the ground up. I learned how to think about timing, inputs/outputs, and hardware-software interaction in a real-world context. I’m excited to apply this knowledge to future IoT projects.

Thanks for a great term!
