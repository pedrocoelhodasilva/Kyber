## Electronic voting implementation of CRYSTALS-Kyber

According to the [official website](https://pq-crystals.org),

>The "Cryptographic Suite for Algebraic Lattices" (CRYSTALS) encompasses two cryptographic primitives: [Kyber](https://pq-crystals.org/kyber/index.shtml), an IND-CCA2-secure key-encapsulation mechanism (KEM); and [Dilithium](https://pq-crystals.org/dilithium/index.shtml), a strongly EUF-CMA-secure digital signature algorithm. Both algorithms are based on hard problems over module lattices, are designed to withstand attacks by large quantum computers, and have been submitted to the [NIST post-quantum cryptography project](https://csrc.nist.gov/Projects/Post-Quantum-Cryptography).

As for [Kyber](https://pq-crystals.org/kyber),

>[it] is an IND-CCA2-secure key encapsulation mechanism (KEM), whose security is based on the hardness of solving the learning-with-errors (LWE) problem over module lattices. Kyber is one of the finalists in the [NIST post-quantum cryptography project](https://csrc.nist.gov/Projects/Post-Quantum-Cryptography).

Authors

>recommend using the Kyber-768 parameter set, which—according to a very conservative analysis—achieves more than 128 bits of security against all known classical and quantum attacks.

Only this set and the IND-CPA-secure encryption will be considered. Ignoring the compression. Performance is not relevant.
<br />
<br />

More details about Kyber in the [algorithm specifications and supporting documentation](https://pq-crystals.org/kyber/data/kyber-specification-round3-20210804.pdf) and in the original paper:

>Cryptology ePrint Archive, Paper 2017/634, 2017. https://eprint.iacr.org/2017/634
