This project focuses on the design and simulation of an OFDM receiver capable of estimating and mitigating key RF impairments such as Carrier Frequency Offset (CFO), Phase Noise, and IQ Imbalance. These impairments arise due to oscillator mismatches and hardware imperfections, leading to performance degradation in practical wireless systems.

A hybrid pilot-aided and data-aided approach is used for joint estimation. The OFDM signal is generated at the transmitter, where controlled impairments are introduced to replicate real-world conditions. The signal is then transmitted through a channel and processed at the receiver.

At the receiver, synchronization techniques are applied to estimate and correct CFO, while phase noise is tracked and compensated to reduce signal distortion. IQ imbalance is analyzed to detect mismatches between in-phase and quadrature components. System performance is evaluated using Bit Error Rate (BER).

The results demonstrate successful estimation of impairments, though the observed BER indicates scope for improving compensation techniques. Implemented in MATLAB, this project highlights practical challenges in wireless receiver design and provides a strong foundation for understanding OFDM-based systems used in modern communication standards like LTE and 5G.
