# MATLAB BER Performance Analyzer

This project implements an **object-oriented BER (Bit Error Rate) analyzer in MATLAB** for digital communication systems.  
It supports multiple modulation schemes and channel models with **BER vs SNR performance visualization**.

---

##  Features
- BPSK, QPSK, and M-QAM support
- AWGN, Rayleigh, and Rician channel models
- BER vs SNR performance plots
- Theoretical vs simulated BER comparison
- Modulation order comparison
- Required SNR estimation for target BER
- OOP-based reusable MATLAB framework

---

##  Project Structure
```text
matlab-ber-performance-analyzer/
│
├── BERAnalyzer.m
├── testBERAnalyzer.m
├── README.md
├── command_line_output.txt
│
├── results/
│   ├── ber_vs_modulation_order.png
│   ├── required_snr_analysis.png
│   └── test_result.png
```

---

##  How to Run
Run the test script in MATLAB:

```matlab
run('testBERAnalyzer.m')
```

---

## OUTPUTS 
### BER vs Modulation index 
![Processor Screenshot](https://github.com/shreyasingh2302vl10/Bit_Error_Rate_Analyser/blob/fdcc8f9edcc2bce91683af84d63c8463b742d125/BER_Modulation_Index.png)
### BER vs SNR 
![Processor Screenshot](https://github.com/shreyasingh2302vl10/Bit_Error_Rate_Analyser/blob/fdcc8f9edcc2bce91683af84d63c8463b742d125/BER_SNR.png)
### SNR vs MODULATION SCHEME
![Processor Screenshot](https://github.com/shreyasingh2302vl10/Bit_Error_Rate_Analyser/blob/9d07950ec53bf6a0df060ec606e1482b4adfd761/Screenshot%202026-03-31%20202209.png)
##  Applications
- Digital communication systems
- Wireless receiver analysis
- OFDM performance study
- 5G physical layer simulation
- BER validation and testing

---

