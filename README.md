🔋 Solar Inverter Using SG3524 PWM Controller
📌 Project Overview

This project presents the design and implementation of a 12V DC to AC Solar Inverter System using the SG3524 PWM controller IC. The system converts solar energy stored in a battery into usable AC power for low-power household applications.

The project includes:

Circuit design and modelling

Proteus simulation

Hardware implementation

Component-level technical analysis

⚙️ System Architecture

Solar Panel → Charge Controller → Battery → PWM Inverter Circuit → Step-Up Transformer → AC Output

🧩 Key Components

12V, 10W Solar Panel

12V, 4.5Ah Rechargeable Battery

SG3524 PWM Controller IC

TIP41 NPN Power Transistors

1N4007 Diode

Step-Up Transformer

Passive components (Resistors, Capacitors)

🔁 Working Principle

Solar panel charges the 12V battery.

SG3524 generates 50Hz PWM signals.

TIP41 transistors operate in push-pull configuration.

Transformer steps up 12V AC to higher AC voltage.

Output measured ≈ 11.19V AC (as per hardware testing).

🧮 Frequency Calculation

Frequency = 1 / (2 × RT × CT)

RT = 100KΩ
CT = 0.1µF

Output frequency ≈ 50Hz

💻 Software Used

Proteus 8 Professional
(TL494 used in simulation due to SG3524 library limitation)

🛠 Hardware Implementation

The hardware prototype includes:

Solar charging section

Sealed lead-acid battery

Breadboard inverter circuit

Transformer output stage

📊 Results

Stable 50Hz PWM output

AC output ≈ 11.19V

Successful DC to AC conversion

Functional prototype tested

📈 Future Improvements

Replace TIP41 with MOSFETs for higher efficiency

Add MPPT charge controller

Add microcontroller-based monitoring

Improve waveform to pure sine wave

Add LCD voltage display

Design PCB instead of breadboard

🌱 Applications

Rural power backup

Small household loads

Renewable energy education

UPS systems

Low-power emergency supply

📚 References

(Include your 5 papers listed in the report)
