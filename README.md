# 1_Bit_Adder

This project involves the design and optimization of a 1-bit full adder using complementary static CMOS logic with 28 transistors. The goal is to achieve a circuit with minimal delay and power consumption while addressing issues such as global and local mismatch and parasitics.

The circuit design was implemented using a 45 nm TSMC library, and transistor sizing was done to achieve similar tpLH and tpHL values. A buffer was added to each input to prevent signal source interference, and a 10fF capacitor load was given to both outputs. The layout of the circuit was designed using M1 and M2 metal layers, and a functional simulation was performed to validate its operation.

To evaluate the circuit's performance, worst-case delay, average power consumption, and power delay product were analyzed under various process corners and temperatures. The SS corner had the highest delay due to slow nmos and pmos, while the FF corner had the lowest delay.

Additionally, 100 Monte Carlo simulations were performed to analyze local mismatch, and the results showed that the circuit was robust to variations in transistor characteristics.

Overall, the designed 1-bit full adder achieved minimal delay and power consumption while addressing various issues associated with VLSI circuits.
