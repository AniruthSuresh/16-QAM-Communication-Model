# 16-QAM Communication Model

## Project Overview

This project focuses on developing and simulating a communication system utilizing 16-QAM (Quadrature Amplitude Modulation). 16-QAM is a modulation technique widely used in digital communication systems to transmit digital data over radio and optical communication channels. The project involves encoding digital information into 16-QAM symbols, transmitting them through a simulated channel, and decoding them to recover the original data.

### Modulation Scheme

16-QAM uses 16 different amplitude and phase combinations to encode four bits per symbol. This balance between data rate and spectral efficiency makes 16-QAM ideal for applications where both factors are crucial. Each symbol in 16-QAM represents a unique combination of amplitude and phase, allowing for efficient data transmission.

![16-QAM Constellation](https://github.com/user-attachments/assets/117ba468-1757-4457-a46d-a0379079046e)

### System Components

#### Transmitter

The transmitter encodes digital data into 16-QAM symbols. It uses root-raised cosine pulses for pulse shaping, which helps in minimizing intersymbol interference and improving signal quality.

![Transmitter Block Diagram](https://github.com/user-attachments/assets/f08f4927-c300-40f6-88c8-531c491e516f)

#### Receiver

The receiver demodulates the received symbols to recover the original data. It includes a matched filter to process the signals shaped by root-raised cosine pulses, and performs decoding and error correction to ensure accurate data retrieval.

![Receiver Block Diagram](https://github.com/user-attachments/assets/961f5ec7-9d8a-4d21-95cb-9dc48e6d625a)

### Performance Evaluation

The project evaluates the Bit Error Rate (BER) of the communication system across different levels of Signal-to-Noise Ratio (SNR) for both memory and memoryless AWGN (Additive White Gaussian Noise) channels. Additionally, BER vs. SNR curves are plotted to analyze system performance under varying noise conditions.

This model provides valuable insights into 16-QAM modulation, the use of root-raised cosine pulses for signal shaping, and its performance in digital communication systems.
