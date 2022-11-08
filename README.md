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
One of the challenges in comparing a classical vs. quantum proof of work algorithm is creating a hash function implementable both in classical and quantum terms. Here is our take:
[Quantum Hash](https://github.com/Anastasia-Sim/PoW-QCSA-fa22/blob/main/QuantumHash.ipynb)

Using the hash created above, we integrate with Grover's search to find a far more superior search algorithm than classical brute force:
[Quantum Proof-of-Work](https://github.com/Anastasia-Sim/PoW-QCSA-fa22/blob/main/Quantum_PoW.ipynb)

# Comparison
![Screenshot](pictures/findings.png)

# Extras
Though these results are exciting, we also tried our hand at a more realistic quantum proof of work circuit that involved nonces (https://coincentral.com/what-is-a-nonce-proof-of-work/). Though we got close to a working implementation, we did not have enough resources at hand to complete. Thus, we have linked it in the extras folder as extra goodies from our quantum exploits!

# Thank You!
Big shoutout to the UCLA QCSA for organizing! This was a lot of fun!
