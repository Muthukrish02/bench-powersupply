
![Screenshot 2024-11-03 122616](https://github.com/user-attachments/assets/f4eb8cc1-e2be-4007-b645-68b3ae15519d)
Variable DC Power Supply with Digital Display

This project is a Variable DC Power Supply designed to provide an adjustable output voltage with a real-time digital display for both voltage and current. It uses an AC to DC conversion system with a transformer, bridge rectifier, and smoothing capacitor, followed by a regulation circuit for precise output control. This power supply is suitable for electronics enthusiasts, engineers, and students looking for a reliable, adjustable power source for testing or powering circuits.

# Features

   AC to DC Conversion: Converts AC mains voltage to a stable DC voltage.
    Adjustable Output Voltage: Fine-tune the output voltage from 1.25V up to around 24V.
    Current Amplification: Uses TIP3055 transistor for handling higher currents.
    Digital Display: Real-time monitoring of voltage and current.
    Over-Temperature Protection: Cooling fan for safe operation at higher loads.
    Reverse Polarity Protection: Protects the circuit from incorrect connections.

# Components Used

   Step-Down Transformer: Lowers AC mains voltage to a manageable level.
    Bridge Rectifier (10A): Converts AC to DC.
    2000µF Capacitor: Smooths out ripple in the DC supply.
    LM317 Voltage Regulator: Adjustable voltage regulation.
    LM7805: Provides 5V supply for the digital display.
    BD139 and TIP3055 Transistors: For current amplification.
    IN4007 Diodes: Reverse polarity protection.
    Digital Voltmeter/Ammeter Display: Real-time voltage and current display.
    Cooling Fan: Keeps the circuit cool during high load conditions.
    Resistors and Potentiometer: For setting voltage and current limits.

# Circuit Operation

   AC to DC Conversion: An AC input is stepped down by the transformer and then rectified by a 10A bridge rectifier. A 2000µF capacitor smooths the DC voltage, minimizing ripple.
    Voltage Regulation: The smoothed DC is regulated by the LM317, with the output adjustable via a potentiometer.
    Current Amplification: BD139 and TIP3055 transistors enable the circuit to handle larger currents.
    Thermal Management: The cooling fan maintains safe temperatures.
    Digital Monitoring: The digital display shows real-time voltage and current.

Circuit Diagram

Refer to the circuit schematic above or the circuit_schematic.jpg file in this repository for details.
How to Use

   Connect to AC Power: Plug the transformer into an AC outlet.
    Adjust Voltage: Use the potentiometer to set the desired output.
    Monitor Display: Check the voltage and current readings on the display.
    Safety: Ensure proper ventilation for the fan and heat sinks on TIP3055 for continuous high current usage.
# Technical Specifications

   Input Voltage: AC mains (transformer output depends on transformer specification, e.g., 12V AC or 24V AC).
    Rectified DC Voltage: Approximately 16-32V DC after bridge rectifier and capacitor.
    Output Voltage: Adjustable from 1.25V up to ~24V.
    Max Output Current: Depends on TIP3055 dissipation and transformer rating.
    Capacitor: 2000µF for DC smoothing.

# Applications

  Electronics Testing: Provides adjustable power for circuit testing.
    DIY Projects: Great for powering low-power electronics projects.
    Educational: Demonstrates power supply design and regulation principles.

# Troubleshooting

  No Output: Check connections on the transformer, rectifier, and LM317.
    Voltage Fluctuations: Confirm capacitor connections and grounding.
    Overheating: Ensure fan and heat sink are functioning.

# License

This project is licensed under the MIT License.s
