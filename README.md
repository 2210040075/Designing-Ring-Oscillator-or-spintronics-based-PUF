![image](https://github.com/user-attachments/assets/ddd9f4dc-0d98-4737-aa6b-df0bd030cef0)# Designing-Ring-Oscillator-or-spintronics-based-PUF
## Introduction:
Hardware security has become increasingly important over the last few years due to security threats such as reverse engineering, cloning, and secret extraction from integrated circuits (ICs). A physical unclonable function (PUF) based on Ring Oscillator (RO) technology is examined in this project as a hardware security measure. As a result of inherent manufacturing variations, PUFs provide unique, device-specific responses, making them a valuable tool for applications requiring secure key generation and device authentication.

## Project Objectives:
1.Design an RO-based PUF that offers a higher number of challenge-response pairs (CRPs).
2.Improve PUF reliability under varying environmental conditions by leveraging relative frequency values.
3.Implement the design on FPGA platforms to evaluate performance metrics such as reliability, uniformity, and bit aliasing.

## CMOS Inverter-Based Ring Oscillator: 
This basic ring oscillator consists of a loop of CMOS inverters, known for their simple implementation and low power consumption. In Ring Oscillator (RO) Physical Unclonable Functions (PUFs), an array of ring oscillators generates unique device signatures by oscillating at frequencies influenced by small manufacturing variations. Each oscillator's frequency differences yield a unique binary signature for each device, which is consistent but difficult to replicate. Despite their effectiveness, CMOS inverters can be sensitive to environmental changes, such as temperature and voltage variations, affecting performance and PUF reliability.
![image](https://github.com/user-attachments/assets/2a2d019d-1670-4498-90ad-e1e10632c66d)



