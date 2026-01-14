# PCB_Design
📌 3rd Order Analog Filter
📖 Project Description

This project presents the hardware realization of a 3rd order analog filter through a custom-designed PCB. The objective is to implement a higher-order filtering network that achieves improved frequency selectivity and sharper attenuation compared to first- and second-order filters, while maintaining stability and low noise performance.

A 3rd order filter theoretically provides a roll-off of −60 dB/decade, making it suitable for precision analog signal conditioning.

⚙️ Filter Architecture

The filter is implemented by cascading:

A first-order RC stage, and

A second-order active filter stage

This modular architecture simplifies analysis, tuning, and PCB layout while ensuring predictable frequency response and controlled phase behavior.

🧩 PCB Design Facts

Two-layer PCB (Front and Bottom copper)

Optimized analog signal routing to minimize parasitic capacitance and inductance

Short trace lengths in critical signal paths to reduce noise pickup

Proper ground return paths for stable analog performance

Through-hole mounting for mechanical robustness and ease of prototyping

Fabrication-ready Gerber and drill files are included in the repository.

🧪 Performance & Applications

High attenuation beyond cutoff frequency

Stable operation over component tolerances

Suitable for audio filtering, sensor signal conditioning, and communication front-ends

📝 Technical Summary

This project demonstrates the translation of analog filter theory into a manufacturable PCB design, highlighting practical considerations such as layout integrity, grounding, and real-world component behavior.
