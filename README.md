# 🔋 Solar Inverter Using SG3524 PWM Controller

## 📌 Project Overview

This project presents the design and hardware implementation of a **12V DC to AC Solar Inverter** using the SG3524 PWM controller IC. The system converts solar energy stored in a rechargeable battery into usable AC power for low-power applications.

The inverter operates at 50Hz and uses a push-pull topology with a step-up transformer to generate AC output.

---

## ⚙️ System Architecture

Solar Panel → Charge Controller → 12V Battery → SG3524 PWM Inverter → TIP41 Transistors → Step-Up Transformer → AC Output

---

## 🧩 Components Used

* 12V, 10W Solar Panel
* 12V, 4.5Ah Rechargeable Battery
* SG3524 PWM Controller IC
* TIP41 NPN Power Transistors
* 1N4007 Diode
* Resistors (100K, 4.7K, 100Ω, 1K, 20K)
* Capacitors (0.1µF, 0.01µF, 100µF)
* Step-Up Transformer
* Breadboard & Connecting Wires

---

## 🔁 Working Principle

1. The solar panel charges the 12V rechargeable battery.
2. The SG3524 IC generates 50Hz PWM signals.
3. The PWM signals drive two TIP41 transistors in push-pull configuration.
4. The transformer steps up the 12V AC to a higher AC voltage.
5. The output is supplied to small AC loads.

---

## 🧮 Frequency Calculation

The inverter frequency is determined by RT and CT values:

Frequency = 1 / (2 × RT × CT)

RT = 100KΩ
CT = 0.1µF

Calculated frequency ≈ 50Hz

---

## 📊 Results

* Stable PWM operation at 50Hz
* AC Output measured ≈ 11.19V
* Successful DC to AC conversion
* Hardware prototype tested and validated

---

## 🛠 Hardware Implementation

The project was implemented on a breadboard and tested using:

* Solar charging section
* Sealed lead-acid battery
* PWM inverter circuit
* Transformer output stage

---

## 🌱 Advantages

* Renewable energy based system
* Simple and low-cost design
* Suitable for small household loads
* Can be used as backup power supply

---

## 🚀 Future Improvements

* Replace BJT (TIP41) with MOSFETs for higher efficiency
* Add MPPT charge controller
* Convert square wave to pure sine wave
* Add LCD monitoring system
* Design custom PCB

---

## 📚 References

[1] M. Ranjan, S. S. Bidgar, P. P. Satish, W. A. Bibhishan, and M. Kalgonde, “Solar Inverter Project,” International Journal of Advanced Research in Science, Communication and Technology (IJARSCT), vol. 3, no. 9, May 2023.

[2] I. N. Abubakar and Jonahs, “Design and Implementation of a 1.5 kVA Solar Powered Inverter,” Journal of Science Technology and Education, vol. 8, no. 3, Sept. 2021, ISSN: 2277-0011.

[3] N. Siddiqui, M. Anwar, J. Akhtar, E. Asif, M. Rehan, and T. Khan, “Design and Implementation of Solar Panel MPPT with Inverter and Battery Towards Load Side,” International Journal of Scientific Research in Science and Technology, ISSN: 2395-6011 (Print), 2395-602X (Online).

[4] F. O. Ehiagwina, A. S. Nafiu, I. S. Olatinwo, O. O. Kehinde, and M. A. Ibrahim, “Development and Installation of a 1.5 kVA Solar Powered Inverter System for a Mini-ICT Centre,” International Journal of Circuit, Computing and Networking, vol. 2, no. 2, pp. 01-09, 2021.

[5] P. Prakash, S. Nandha Kumar, K. Sathish Kumar, and S. Sreejith, “IoT Based Smart Solar Inverter for Solar Power Generation,” International Journal of Advance Research, Ideas and Innovations in Technology, vol. 9, no. 2, 2023, ISSN: 2454-132X.


