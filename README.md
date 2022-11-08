# Quantum Cryptography : Proof of Work

**Team members**: Jenny Chen, Jeffrey Kwan, Seongbin Park, Anastasia Simonova, John Wang

## Summary
Our team used Quantum Grover’s search to significantly decrease the compute time it takes to do proof-of-work -- technology used by Bitcoin to approve addition of blocks to the blockchain. We use a four-bit system to compare performance of classical vs. quantum proof-of-work. The simplified model demonstrates the impact quantum computers can have with a greater number of qubits at their disposal.

### Goal:
Compare Grover’s search with classical “mining” algorithms in obtaining proof-of-work.

## Roadmap
1. Classical Proof-of-Work
2. Quantum Implementation
3. Comparison
4. Conclusion

# Classical Proof-of-Work
Classically, proof-of-work is an algorithm that ensures entities have undertaken enough computational work before adding blocks & completing transactions. An example of such an algorithm is SHA256 Hash Algorithm.

In our implementation, we use a parity of our our own hash that utilizes 4 bits to encode information and utilise brute force. The link to our notebook is 
[here](https://github.com/Anastasia-Sim/PoW-QCSA-fa22/blob/main/Classical_PoW.ipynb).

# Quantum Implementation
[Quantum Hash](https://github.com/Anastasia-Sim/PoW-QCSA-fa22/blob/main/QuantumHash.ipynb)

[Quantum Proof-of-Work](https://github.com/Anastasia-Sim/PoW-QCSA-fa22/blob/main/Quantum_PoW.ipynb)

# Comparison
![Screenshot](pictures/findings.png)

# Conclusion
