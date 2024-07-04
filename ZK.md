# Learn-ZK

## Initial topics to Learn
 - Maths
 - Sequences / Series
 - Group theory
 - Fields
 - Extension field
 - Calculus
 - Discrete Math
 - Polynomials
 - Irreducible polynomials (Eisenstein's criterion)
 - Cryptography
 - Elliptic curves
 - Crypto book by Koblitz
 - Videos by https://zk-learning.org/
 - Complexity theory and advanced algorithms (Thomas H. Cormen)
 - Operating systems (Avi Silberschatz)
 - Processors
 - Microprocessor 8085 (Ramesh Goankar)
 - NTT and FTT — https://cgyurgyik.github.io/posts/2021/04/brief-introduction-to-ntt/

# Resources
 - ZK whiteboard series https://www.youtube.com/playlist?list=PLj80z0cJm8QErn3akRcqvxUsyXWC81OGq
 - Good blog series on SNARK Why and How zk-SNARK Works 2: Proving Knowledge of a Polynomial | by Maksym | Medium
 - Code to polynomials and computation (best explanation) — https://medium.com/@imolfar/why-and-how-zk-snark-works-5-variable-polynomials-3b4e06859e30
 ### ZCash resources
 - ZCash zkSNARK — https://z.cash/technology/zksnarks
 - https://electriccoin.co/blog/snark-explain/
 - Elliptic curve
 - Best elliptic curve and tate pairings explanation — https://medium.com/@VitalikButerin/exploring-elliptic-curve-pairings-c73c1864e627
 - **BEST Gentle Introduction https://andrea.corbellini.name/2015/05/17/elliptic-curve-cryptography-a-gentle-introduction/**
 - Best elliptic curve explanation — https://electriccoin.co/blog/snark-explain7/
 - BLS12-381 — https://hackmd.io/@benjaminion/bls12-381 (So the thing is you need large subgroups over that field, each of the same order, say r. And you need two of them, to get G1 and G2, over which the pairing function is defined. So what you do, is you keep extending the field to get such subgroups. How much you extend is called the embedding degree of it.)
 - Curves for ZK Proofs (Base field vs. Scalar field)
 - https://zcash.github.io/halo2/background/curves.html
 - Code and learn
 - https://dev.to/spalladino/a-beginners-intro-to-coding-zero-knowledge-proofs-c56
 - Learn while coding — https://github.com/lambdaclass/lambdaworks
 - Elliptic curve explanation (Implementation wise) — https://cryptobook.nakov.com/asymmetric-key-ciphers/elliptic-curve-cryptography-ecc
 - FFT / NTT (Fast fourier transform)
 - Vitalik’s post — https://vitalik.ca/general/2019/05/12/fft.html
 - Polynomial commitments (Others are Multilinear and Linear commitments) ****similar to commit-and-prove
 - Basic elliptic curves — Bulletproofs
 - Bilinear groups
 - KZG (Kate commitment)
 - Links — https://scroll.io/blog/kzg // https://dankradfeist.de/ethereum/2020/06/16/kate-polynomial-commitments.html
 - BLS12-381 — https://hackmd.io/@benjaminion/bls12-381
 - Dory
 - Groups of unknown order — DARK’20
 - Hash-based — FRI (For STARK)
 - https://www.youtube.com/watch?v=L7tZeO8ihcQ
 - https://www.youtube.com/watch?v=Jliz19njGkg (Why RS code is using in FRI and what is motivation of FRI — very important to understand)
 - Paper — https://drops.dagstuhl.de/opus/volltexte/2018/9018/pdf/LIPIcs-ICALP-2018-14.pdf
 - https://hackmd.io/@olivierbbb/By1dILSV8 (Pre-read before you read FRI)
 - https://www.youtube.com/watch?v=txo_kPSn59Y&list=PLcIyXLwiPilWvjvNkhMn283LV370Pk5CT (DEEP FRI)
 - https://www.risczero.com/docs/reference-docs/about-fri
 - Multi folding — factor by 2,4.. in Winterfell https://github.com/facebook/winterfell/blob/main/fri/src/folding/mod.rs#L21
 - Polynomial IOP (Interactive Oracle Proofs)

 ### PLONK
 - PLONK — Python notebook with code — https://github.com/ETHorHIL/Plonk_Py/blob/master/plonk_tutorial.ipynb
 - https://www.cryptologie.net/article/527/understanding-plonk/ (Very easy way to get an overview of PLONK)
 - https://cryptologie.net/article/529/how-does-plonk-work-part-1-whats-plonk/ (Good short videos on PLONK)
 - https://www.youtube.com/watch?v=A0oZVEXav24 (BEST video on PLONK by dan boney)
 - PLONK Arithmetization - HackMD
 - From AIRs to RAPs - how PLONK-style arithmetization works - HackMD
 - https://trapdoortech.medium.com/zkp-plonk-algorithm-introduction-834556a32a (Explains with Rounds)
 - https://2π.com/19/plonks-permutation-check/ (PLONK permutation check)
 - https://hackmd.io/@arielg/ByFgSDA7D (Multiset checks in PLONK and Plookup)
 - https://hackmd.io/@aztec-network/BkGNaHUJn/%2FGfNR5SE5ShyXXmLxNCsg3g (Goblin Plonk)
 
 ### FFLONK
 - https://hackmd.io/gUdGy0R8Qo2kxhIfL8H74Q?view (zkEVM / Hermez code)
 - https://eprint.iacr.org/2021/1167.pdf
 - Recursive proofs
 - ZK Pairings https://0xparc.org/blog/zk-pairing-1 // https://0xparc.org/blog/zk-pairing-2
 - https://www.youtube.com/watch?v=0LW-qeVe6QI&feature=youtu.be (Lacture from zkp mooc)
 - Batch proofs
 - https://www.youtube.com/watch?v=ZwG3UI_iDAs (Jordi’s presentation at Hermez)
 - SNARK — Succinct Non-Interactive Zero Knowledge for a von Neumann Architecture
 - https://eprint.iacr.org/2013/879.pdf

### STARK
 - Paper — https://eprint.iacr.org/2021/582.pdf
 - https://www.youtube.com/watch?v=A3edAQDPnDY (Best Video from Justin Thaler on FRI and transparent ZK — )
 - https://www.youtube.com/watch?v=9VuZvdxFZQo (First class from Eli — BEST one on low-degree testing and RS code for FRI and Arithmetization)
 - https://www.youtube.com/watch?v=L7tZeO8ihcQ (Second class from Eli)
 - https://starkware.co/stark-101/ (STARK 101)
 - https://medium.com/starkware/tagged/stark-math
 - https://medium.com/starkware/stark-math-the-journey-begins-51bd2b063c71
 - https://medium.com/starkware/starkdex-deep-dive-introduction-7b4ef0dedba8
 - https://aszepieniec.github.io/stark-anatomy/
 - https://starkware.co/stark-101/
 - https://twitter.com/bkiepuszewski/status/1481521079562784769 (Good twitter thread on STARK)
 - https://hackmd.io/@liamzebedee/H1ejQCoHj (Notes — What is the anatomy of a STARK proof? Very good notes)
 - https://cronokirby.com/posts/2022/09/notes-on-stark-arithmetization/ (Excellent notes on stark Arithmetization — explains the satisfiability of an arithmetic system is reduced to a problem of low-degreeness of a polynomial
 - Vitalik’s notes on it — https://hackmd.io/@vbuterin/snarks#Can-we-have-one-more-recap-please
 - https://www.youtube.com/watch?v=2udp2V_C0xY (Talks about PCPs and low-degree testing + encoding in simple terms)
 - https://vitalik.ca/general/2017/11/22/starks_part_2.html (Vitalik’s post explains why RS code is required before FRI)
 - https://vitalik.ca/general/2017/11/09/starks_part_1.html
 - Fiat-Shamir
 
### ZkEVM
 - zkEVM - HackMD
#### Hardware acceleration
 - Paradigm — https://www.paradigm.xyz/2022/04/zk-hardware
 - https://blog.janestreet.com/zero-knowledge-fpgas-hardcaml/ (MSM)
### MSM (Multi scaler multiplication)
 - https://www.youtube.com/watch?v=Bl5mQA7UL2I

### Poseidon
 - https://eprint.iacr.org/2019/458.pdf
 - PLONKISH—Arithmetization
 - https://docs.zkproof.org/pages/standards/accepted-workshop3/proposal-turbo_plonk.pdf
 - https://hackmd.io/@aztec-network/plonk-arithmetiization-air (PLONK Arithmetization AIR)
 - https://zcash.github.io/halo2/concepts/arithmetization.html
 - https://hackmd.io/@jake/plonk-arithmetization (Best on PLONK arithmetization)
 
 ### PLOOKUP
 - https://www.youtube.com/watch?v=Vdlc1CmRYRY (Video from Zac and Ariel)
 - https://research.metastate.dev/on-plonk-and-plookup/
 - https://fluid-dex.medium.com/on-the-optimization-of-plonk-87797f5942cd
 - https://eprint.iacr.org/2020/315
 - https://eprint.iacr.org/2020/315.pdf
 - https://github.com/caulk-crypto/caulk
 - https://zcash.github.io/halo2/design/proving-system/lookup.html
 - https://hackmd.io/@7dpNYqjKQGeYC7wMlPxHtQ/BJpNmNW0L
 
 ### Miden VM
 - https://hackmd.io/@bobbinth/H1aCWWy7F
 - https://github.com/0xPolygonMiden/miden-vm/issues/65
 
 ### Goldilocks
 - https://2π.com/22/goldilocks/

 ### Stack vs Memory-based zkVM
 - https://github.com/0xPolygonMiden/miden-vm/issues/65
 
 ### Recursion
 - https://www.youtube.com/watch?v=-pucWUDn5Hw&list=PLj80z0cJm8QErn3akRcqvxUsyXWC81OGq&index=15
 - R1CS arithmetic circuits
 - https://tlu.tarilabs.com/cryptography/rank-1#introduction
 
 ### Setup and CRS/SRS
 - https://hackmd.io/@Serg10JV/ByMbUBzoc
 - https://eprint.iacr.org/2017/1050.pdf  (Random Beacon Model)
 - https://trapdoortech.medium.com/zkp-deep-dive-into-powersoftau-670bd2089a08
 - https://vitalik.ca/general/2022/03/14/trustedsetup.html
 - Groth16 and Setup — https://2π.com/22/groth16/
 
 ### Lagrange polynomials
 - https://hackmd.io/@vbuterin/barycentric_evaluation
 - Montgomery Reduction and multiplication
 - https://www.youtube.com/watch?v=hUl8ZB6hpUM
 - https://en.algorithmica.org/hpc/number-theory/montgomery/

## Finite Field / Group
- http://math.ucdenver.edu/~wcherowi/courses/m6406/finflds.pdf
- Two adicity — https://www.cryptologie.net/article/559/whats-two-adicity/
- https://www.rieselprime.de/ziki/Quadratic_residue
- https://www.rieselprime.de/ziki/Modular_square_root
- https://www.dcode.fr/euler-totient
- ZK Snarks and Their Algebraic Structure - Part 4 - Coder's Errand
- Interactive Oracle Proofs — https://www.iacr.org/archive/tcc2016b/99850156/99850156.pdf
- https://blog.chain.link/computation-complexity-metrics/
- https://blog.chain.link/interactive-zero-knowledge-proofs/
- DEEP FRI video: https://youtu.be/txo_kPSn59Y?list=PLcIyXLwiPilWvjvNkhMn283LV370Pk5CT
- Bobbin’s sessions - only take at the topics which interest you: https://www.notion.so/polygontechnology/Sessions-on-Proofs-of-Computational-Integrity-by-Bobbin-Threadbare-477fedcfd19b47cc8aead6ea200f0a25
- Plonky2 — https://github.com/mir-protocol/plonky2/blob/main/plonky2/plonky2.pdf
- OLA VM — https://github.com/Sin7Y/olavm
- KZG — https://scroll.io/blog/kzg
- FTT — https://medium.com/@xinyu.chen/discrete-convolution-and-fast-fourier-transform-explained-and-implemented-step-by-step-83ff1809378d
- Goldilocks NTT — Ingonyama Blog
- (For an elliptic curve defined over prime field F_p, a generator g of that curve’s group doesn’t necessarily have order p-1.
- Yet e.g. KZG seems to rely on being able to multiply gx for any x in F_p.
- So do we just pick curves with generators that are known to have order p-1? How?)
- https://twitter.com/a_kirillo/status/1627365058962690048
- Euler’s phi function/totient function

## Trusted Setup

- https://medium.com/@imolfar/why-and-how-zk-snark-works-6-verifiable-computation-protocol-1aa19f95a5cc

## Topics

### Finite Field Algebra
 - Big integer representation
 - Basic algebra: addition, multiplication, subtraction, inversion, square root (Tonelli–Shanks)
 - Field extensions
 - Number theoretic transform
 - Polynomial operations
 - Fast Fourier Transform
 - Montgomery and Barrett

### Elliptic curve models
 - BLS12-381 (H)
 - BLS12-377 (H)
 - secp256k1 (H)
 - Ed25519 (H)
 - Jubjub (M)
 - BN254 (M)
 - Pasta: Pallas and Vesta (L)
 - Forms:
 1 Affine (H)
 2 Projective (H)
 3 Montgomery (M)
 4 Twisted Edwards (H)
 5 Jacobi (L)

### Elliptic curve operations
 - Add, double, scalar multiplication.
 - Multiscalar multiplication (Pippenger)
 - Weyl, Tate and Ate pairings.

### Arithmetization
 - R1CS - gadgets (H)
 - AIR (M)
 - Plonkish (H)
 - ACIR (L)

### Polynomial commitment schemes
 - KZG and variants
 - Hashing
 - Inner product arguments
 - Dory (L)

### PIOP/PCS
 - Groth16
 - Plonk
 - Marlin
 - FRI

### Crypto primitives
 - Pseudorandom generator
 - Hashes
 - Blake2
 - Keccak
 - Poseidon
 - Pedersen
 - Encryption schemes
 - AES
 - ChaCha20
 - Rescue
 - ElGamal

### Protocols
 - Fiat-Shamir

## Security

### STARK
 - STARK in Distaff VM — https://github.com/GuildOfWeavers/distaff/blob/master/src/stark/README.md
 - This talks about how Distaff VM has been implemented. How to check sound-ness, security level, and other security parameters.
 - It uses FRI. It is very interesting to check in production with a proper security level. [level = log(1/rate)*n + r; where rate = degree/blow-up factor, n = number of queries, r = grinding factor]
 - STARK in Winterfell — https://github.com/facebook/winterfell/blob/main/math/README.md
 - This talks about different security level based on the field extension you choose.
 