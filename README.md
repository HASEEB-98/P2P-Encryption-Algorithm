# P2P Communication Protocol

## Overview
This repository contains a JavaScript implementation of a peer-to-peer (P2P) communication protocol. The protocol allows for secure communication between a sender and a receiver by generating common cryptographic seeds based on block rules and solutions exchanged between them.

## Features
- Generation of sender and receiver keys based on block rules
- Matrix generation and solution computation for both sender and receiver
- Encryption and decryption of messages using the generated keys and common seed
- Implementation of various cryptographic functions such as bitwise operations, base64 encoding/decoding, and pseudo-random number generation

## Functions
The main functions provided by the protocol are:

- `newP2P(SorR)`: Initializes the protocol for either sender or receiver.
- `genAB()`: Generates sender keys and matrix, computes the solution, and sends it to the receiver.
- `answer()`: Computes receiver keys and the solution from the received data.
- `newCommon()`: Computes the common seed based on the received solution.

Additionally, the protocol includes various helper functions for cryptographic operations, including bitwise operations, base64 encoding/decoding, and pseudo-random number generation.

## About the Author

This compiler was developed by Haseeb-98. For any inquiries or feedback, please feel free to contact me via ahaseeb11.98@gmail.com.


