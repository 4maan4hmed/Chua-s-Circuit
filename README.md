# **Chua’s Circuit – Hardware, Simulation & Double Scroll Attractor**

This repository documents the implementation of **Chua’s Circuit**, a nonlinear electronic system famous for generating the **double-scroll attractor**.
The project includes:

* Hardware circuit construction
* Multisim software simulation
* Oscilloscope visualizations
* Chaotic patterns such as point → limit cycle → bifurcation → double scroll

This README summarizes the project and presents all images that showcase the working setup and results.

---
## **Working Demo**

https://github.com/user-attachments/assets/9d0e00ca-e1a8-4500-bf86-b00c437bbbcc

## **1. Software Simulation (Multisim)**

Before building the physical circuit, the system was modeled in Multisim to identify parameter ranges that produce chaotic behavior.

### **Software Circuit Diagram**

<img width="871" height="369" alt="image" src="https://github.com/user-attachments/assets/a6d3642b-5c59-465d-9252-ccb0153c322c" />


### **Simulation Setup**

<img width="871" height="445" alt="image" src="https://github.com/user-attachments/assets/1c05e4b6-d434-4fc6-b2c9-c35d080b7cbe" />


Simulation helped determine suitable resistor and capacitor values and provided the expected bifurcation behavior before hardware testing.

---

## **2. Hardware Implementation**

The circuit was recreated using:

* TL082 operational amplifiers
* Linear resistors & capacitors
* Potentiometers (2 kΩ) to vary the nonlinear breakpoints

### **Hardware Circuit**

![Hardware Circuit](https://github.com/user-attachments/assets/4ed2f399-d1fc-4186-b214-cc8da81f3402)


Potentiometers were tuned to navigate through different dynamical regimes.

---

## **3. Observed Patterns (Hardware + Software)**

By adjusting the potentiometers, the following progression of the system's behavior was observed:

---

### **Initial Stable Point**

Pot1 ~ 30%, Pot2 ~ 70%

![IMG-20231108-WA0042](https://github.com/user-attachments/assets/a518776a-e8b5-4020-9561-2eb000016294)

---

### **Limit Cycle (Circular Orbit)**

Pot1 ~ 35%, Pot2 ~ 70%
![IMG-20231108-WA0041](https://github.com/user-attachments/assets/7b6e918f-90d8-41dc-b6f4-cd9aeaec5a61)


---

### **Partial Scroll / Pre-Chaotic Behavior**

Pot1 ~ 45%, Pot2 ~ 70%
![IMG-20231108-WA0040](https://github.com/user-attachments/assets/7e8ff6da-ef9e-4495-8bf5-cc123b5954c8)


---

### **Double Scroll – Hardware Output**

Pot1 ~ 60%, Pot2 ~ 70%
![IMG-20231108-WA0045](https://github.com/user-attachments/assets/7662c891-fc47-477f-975c-f9ea81622699)


---

### **Double Scroll – Software Output**



The close similarity between software and hardware validates the correctness of the implementation.

---

---

## **5. Summary**

This project successfully demonstrates:

* Construction of Chua's chaotic circuit
* Achievement of the double-scroll attractor
* Matching behavior between Multisim simulation and real hardware
* Real-time bifurcation tuning using potentiometers

The repository contains only visual documentation (images & GIFs) for reference and presentation.

---
