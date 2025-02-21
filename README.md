<h1 align="center"> awesome-o1js</h1>


![awesome-o1js](https://github.com/user-attachments/assets/b9c8bccc-a1cd-4d9f-80a3-6b11029146a0)

**<p align="center">A curated list of libraries, projects and resources for o1js.</p>**

## Table of Contents


- [Libraries](#libraries)
    - [Math](#math)
    - [Cryptography](#cryptography)
        - [Encryption](#encryption)
        - [Key Exchange](#key-exchange)
        - [Key Generation](#key-generation)
        - [Signatures](#signatures)
        - [Hashing](#hashing)
        - [Provers and Verifiers](#provers-and-verifiers)
        - [Data Structures](#data-structures)
        - [Text](#text)
        - [Privacy](#privacy)
    - [Gaming](#gaming)
- [Projects](#projects)
    - [Socials](#socials)
    - [Gaming](#gaming-1)
- [Experimental & Research](#experimental--research)
- [Dev Tooling](#dev-tooling)
- [Starter Kits](#starter-kits)
- [Tutorials & Documentation](#tutorials--documentation)
- [Presentation & Talks](#presentation--talks)
- [Papers](#papers)
- [Contributions](#contributions)



⚠️ This repository may contain projects that have not been audited. Use them at your own risk in a mainnet product. ⚠️

## Libraries



### Math

- [o1js-math](https://github.com/yunus433/o1js-math/tree/main) - A library for fundamental math operations.
- [o1js-bigint](https://github.com/Shigoto-dev19/o1js-bigint) - A library for a provable bigint type.
- [o1js-matrix](https://github.com/Vishalkulkarni45/o1js-matrix) - A library for matrix operations.
- [o1js GCD](https://github.com/PaimaStudios/o1js-gcd) - A library for in-circuit GCD calculations.

### Cryptography



#### Encryption



- [ChaCha20](https://github.com/0x471/o1js-chacha20/tree/main) - A library for ChaCha20 encryption scheme.
- [o1js-elgamal](https://github.com/Trivo25/o1js-elgamal) -  A library for ElGamal partially homomorphic encryption scheme.
- [o1js rsa](https://github.com/Shigoto-dev19/o1js-rsa/tree/main) - A library for in-circuit RSA verification.

#### Key Exchange



- [ECDH over secp256k1 curve](https://github.com/0x471/o1js-ecdh-secp256k1/tree/main) - A library for ECDH over 256k1 curve.

#### Key Generation



- DKG for Threshold Homomorphic Encryption - A library for distributed key generation.

#### Signatures



- [Schnorr signature verification over secp256k1 in o1js](https://github.com/0x471/o1js-schnorr-secp256k1) - A library for Schnorr signature over secp256k1.
- [Ethereum signature verification in o1js](https://github.com/45930/ethereum-mina-signatures) -  A library for Ethereum signature verification over secp256k1.
- [Multisig Verification in o1js](https://github.com/yunus433/multisig-verification-zkapp/tree/main) - A library for multisig verification in o1js.


#### Hashing

- [Dynamic SHA256](https://github.com/Shigoto-dev19/sha256-o1js) - A library for SHA256 algorithm.
- [Reinforced Concrete](https://github.com/rymnc/reinforced-concrete-impls/) - A library for Reinforced Concrete hash function.

#### Provers and Verifiers


- [Groth16 verifier](https://github.com/onurinanc/o1js-groth16) - A library for Groth16 verifier.
- [o1js-blobstream](https://github.com/geometers/o1js-blobstream) - A library for Gnark-based PLONK & Groth16 verifier.

#### Data Structures


- [o1js-merkle](https://github.com/plus3-labs/o1js-merkle) - A library for Advanced Merkle Tree structures (Sparse Merkle Tree, Standard Merkle Tree and Compact Merkle Tree).

#### Text



- [zkRegex](https://github.com/Shigoto-dev19/zk-regex-o1js) -  A library for regular expression verification.
- [o1js base64](https://github.com/Shigoto-dev19/o1js-base64/tree/main) - A library for  Base64 encoder/decoder.

#### Privacy



- [Private attestations library](https://github.com/zksecurity/mina-attestations/tree/main) - A library for  private attestations.

### Gaming



- [Paima](https://github.com/PaimaStudios/paima-engine) - Provable game engine.
- [ZkNoid](https://github.com/ZkNoid) - An SDK for provable games.

## Projects



#### Socials



- [MRLN](https://github.com/0x471/o1js-rln) - Rate Limiting Nullifier implemented in o1js.
- [o1js Semaphore](https://github.com/Socialcap-app/semaphore-sdk) - Semaphore protocol implemented in o1js.

#### Gaming



- [Dice Roll](https://github.com/YofiY/zk-dice-roll) - A simple dice roll game implemented in o1js.
- [2048](https://github.com/Chomtana/2048-o1js) - 2048 game implemented in o1js.
- [Mastermind](https://github.com/Shigoto-dev19/mina-mastermind/tree/level1) -  Mastermind game implemented in o1js.
- [recursive-gaming](https://github.com/zkzoomer/recursive-gaming/tree/main) - A recursive proof based TicTacToe game implemented in o1js.

## Experimental & Research



Projects in this section are not complete—use them with caution.

- [ZKON](https://github.com/ZKON-Network) - An oracle network that connects Mina blockchain to the off-chain world data.
- [zkEmail](https://github.com/Shigoto-dev19/zk-email-o1js) - zkEmail protocol implemented in o1js.
- [z2zlib](https://github.com/Yeshilabs/z2zlib/tree/version/0.0.1) - P2P state channels implemented in o1js.
- [MMR](https://github.com/codekaya/Mina_MMR) - A library for Merkle Mountain Range.

## Dev Tooling



- [o1js Pack](https://github.com/45930/o1js-pack) - A library that allows to pack extra data into a single Field.

## Starter Kits



- [Scaffold-Mina](https://github.com/DeMonkeyCoder/scaffold-mina) - A starter kit for o1js smart contracts.
- [Protokit starter-kit](https://github.com/proto-kit/starter-kit) - A starter kit for protokit framework.

## Tutorials & Documentation



- [o1js examples folder](https://github.com/o1-labs/o1js/tree/main/src/examples) -  A repository for example use of o1js.
- [Mina Playground](https://www.minaplayground.com/) - Interactive tutorials for o1js.
- [Onboarding to Mina](https://www.youtube.com/watch?v=bJ6BRvFpyk4&list=PLNwigD3FQvjBvYunrf_v2v7lGSeIOpAkx) - Video tutorials for o1js.
- [ZkNoid Blog on Actions & Reducers](https://medium.com/zknoid/mina-action-reducers-guide-why-we-need-them-81b6836c1700) - Blog post series on use of actions&reducers in o1js.

## Presentation & Talks



- [o1js and zk coprocessors](https://www.youtube.com/watch?v=2OroIELozJg) - Florian Kluge on o1js and where it is used.
- [Building Stateful zkApps](https://www.youtube.com/watch?v=aMWDh4minG4) - Boray Saygilier on building zkapps with o1js.
- [What makes Mina so special?](https://www.youtube.com/watch?v=-fG0JLtYlJE) - Nathan Holland explains how Mina and o1js works.

## Papers



- [Project Untitled Paper](https://github.com/o1-labs/project-untitled-whitepaper/blob/main/whitepaper.pdf)
- [Technical Whitepaper](https://minaprotocol.com/wp-content/uploads/technicalWhitepaper.pdf)

## Contributions



The contribution guidelines can be found [here](https://github.com/navigators-exploration-team/awesome-o1js/blob/main/CONTRIBUTING.md).
