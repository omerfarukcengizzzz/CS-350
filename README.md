# CS-350 Final Portfolio - Omer Cengiz

This portfolio highlights two key projects from CS-350: the Morse Code Milestone and the Smart Thermostat Lab. These artifacts represent different parts of the course and showcase what I’ve learned about GPIO control, state machines, LCD interfaces, and hardware-software interaction on the Raspberry Pi.

---

## 🔴 Morse Code Milestone (Module 5)

**Overview:**  
This project uses GPIO LEDs and a button to transmit Morse code messages (`SOS` or `OK`) using a state machine. The 16x2 LCD also displays the current message.

**What I Learned:**  
This was the most challenging but rewarding lab. I learned how to:
- Use state machines to control hardware behavior
- Blink LEDs with precise timing using multithreading
- Build reusable display classes for the LCD
- Use button interrupts effectively

**Why I Chose It:**  
I’m proud of this milestone because it pushed me to really understand timing, concurrency, and state transitions in embedded systems.

---

## 🌡️ Smart Thermostat Lab (Module 7)

**Overview:**  
This was the final lab, combining all prior work. It simulates a smart thermostat that adjusts heating/cooling LEDs based on sensor data and supports three buttons for cycling states and changing temperature. It also uses UART to send updates.

**What I Learned:**  
- Integrating multiple peripherals (LCD, temp sensor, serial port)
- Managing a more complex state machine
- Handling real-time temperature readings and button inputs
- Designing for future scalability (like cloud integration)

**Why I Chose It:**  
This project pulled everything together — sensors, outputs, user inputs, and communication — and made it feel like a real-world IoT system.

---

## 💬 Final Thoughts

CS-350 taught me how to think at the system level. I now understand how hardware and software interact in embedded systems, and I feel confident designing with constraints in mind (timing, GPIO limits, power usage, etc.). I’m excited to keep exploring embedded systems in future projects.
