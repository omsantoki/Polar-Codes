# Polar Codes 

This project investigates **Polar Codes**, a groundbreaking channel coding technique that achieves Shannon’s capacity for binary-input symmetric channels. Polar Codes are at the core of modern communication systems such as **5G**, making them highly relevant for research and industry applications.

## 📌 Key Features

- **Encoding/Decoding** using channel polarization and transformation matrices.
- **BPSK Modulation** and simulation over **AWGN channels**.
- **Successive Cancellation (SC)** and **Successive Cancellation List (SCL)** decoding implemented.
- **LLR-based optimization** to improve decoding accuracy under noisy environments.
- Performance validation through **BER/SNR analysis** and visual plots for **N = 128, 256, 512, 1024**.

## 🔬 Topics Covered

- Channel Polarization Theory & Bhattacharyya Parameter  
- Binary Erasure Channel (BEC)  
- Polar Transform and Encoding  
- SC and SCL Decoding Techniques  
- Simulation Results and Capacity Proofs  
- Comparison with LDPC and Turbo Codes  

## 📊 Results

The project simulates various block lengths (N) and message lengths (K), generating:

- Bit Error Rate (BER)
- Block Error Rate (BLER)
- Success Rates for SC and SCL Decoding

Performance plots demonstrate convergence toward **Shannon’s Capacity Limit** as predicted by theory.

## 🛠 Tools & Technologies

- **MATLAB** for simulation and visualization
- Polar code matrices constructed using **Kronecker products**
- CRC integration in SCL decoding

## 📚 References

- [E. Arikan, Channel Polarization Paper (IEEE)](https://ieeexplore.ieee.org/document/5075875)
- [EventHelix Polar Codes Article](https://medium.com/5g-nr/polar-codes-703336e9f26b)
- [5G NR YouTube Lecture](https://www.youtube.com/watch?v=VhyoZSB9g0w)

## 👥 Contributors

- Daksh Ubhadia  
- Vrund Kansara  
- Tirth Gandhi  
- Jeet Daiya  
- Tirth Koradiya  
- Om Santoki  
- Pal Kaneria  
- Parth Bhatt  
- Tirth Patel  

---

> "Just like polar codes, ignore all the noise and focus only on the good — and your capacity to enjoy life will be maximized."  
> — *Group 2*

