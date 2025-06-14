# 8-Bit-SRAM-Design
This project presents a novel 8-transistor (8T) Static Random Access Memory (SRAM) cell architecture that integrates a Schmitt Trigger-based inverter and a dedicated read buffer transistor. The design aims to address key challenges associated with conventional 6T and 7T SRAM cells, particularly their vulnerability to noise and read disturb issues under low-voltage and high-variation environments. By leveraging the hysteresis property of the Schmitt Trigger in the storage node, the cell significantly enhances noise immunity and strengthens data retention during hold and read operations. Additionally, the inclusion of an isolated read buffer minimizes interference with internal nodes during read operations, thereby improving read Static Noise Margin (SNM) without relying on complex sense amplifiers or dual bit line schemes. Simulation results performed using Cadence Virtuoso and analyzed through butterfly curve methods demonstrate a noticeable improvement in both read and hold SNM compared to traditional 6T, 7T, and Schmitt Trigger-based 7T SRAM cells. The proposed 8T design offers an optimal balance between stability, area overhead, and power consumption, making it a robust solution for modern low-power and high-reliability memory applications, including IoT devices and embedded systems.

OBJECTIVES: 
Comparing Conventional 6T and 7T SRAM Cell with the Schmitt Trigger based 7T Cell.
To improve the Static Noise Margin (SNM) for the operations (like Hold, Read).
Achieve Hold SNM and Read SNM improvement with minimal design changes and transistor count.
Avoid the use of dual bitlines or complex sense amplifiers.
Compare the results by plotting the Butterfly curve.

