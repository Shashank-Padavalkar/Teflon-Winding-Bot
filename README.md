# Semi-Automatic Teflon Tape Winding Machine

This project showcases a **semi-automatic machine** designed to wind **Teflon tape on 2–3 wires or cables** efficiently. Built as a **basic engineering prototype**, the system prioritizes **portability**, **cost-efficiency**, and **usability**.

The machine is **controlled wirelessly** through a **custom mobile app built using MIT App Inventor**, which allows users to start and stop the winding process remotely.

---

## Features

- Winds **2 to 3 cables** simultaneously (each up to **1 cm** in diameter)
- Supports **winding of 1 meter wire in under 5 minutes**
- Entire machine fits within **2 cubic feet**
- Alerts user when **Teflon tape runs out**
- Operates under a budget of **₹4000**
- Portable and easy to assemble
- Controlled via **MIT App Inventor mobile application**

---

## Components Used

| Component                  | Description                      | Approx. Cost (₹) |
|----------------------------|----------------------------------|------------------|
| DC Motor + Driver                 | Drives cable rotation            | 800              |
| Microcontroller (Arduino) | Controls motor and sensor logic  | 1500              |
| Bluetooth Module (HC-05)  | Wireless control via mobile app  | 50              |
| Limit Switch / IR Sensor  | Detects tape depletion           | 40              |
| Power Supply               | Battery or adapter               |200              |
| Frame (Acrylic/Aluminum)  | Housing structure                | 1000             |
| Pulleys / Gears / Rods     | Transmission mechanism           | 300              |
| Misc. Hardware             | Bearings, wires, screws, etc.   | 200              |
| **Total**                  |                                  | **~₹4090**       |

---

## Working Principle

1. **User loads** up to 3 cables onto the machine’s rotating base.
2. The **Teflon tape** is aligned and fixed to the cable using the tape holder mechanism.
3. The user connects to the machine via the **MIT App Inventor mobile app** and presses **Start**.
4. The motor winds the tape around the cable while maintaining uniform tension and speed.
5. A **sensor** detects if the Teflon tape has run out and triggers an alert (buzzer or LED).
6. Pressing **Stop** halts the motor instantly.

---

## Images

### Prototype Design
![Prototype Design](images/prototype.jpg)

### Circuit Diagram
![Circuit Diagram](images/circuit.jpg)

### Final Machine Overview
![Final Machine](images/final_machine.jpg)



---

## Mobile App Control

The control application was developed using **MIT App Inventor** and connects via **Bluetooth** to the machine. It includes:

- Start and Stop buttons  
- Connection status indicator  
- Simple interface for ease of use

You can include the `.aia` file and screenshots in a `mobile_app/` directory if needed.
