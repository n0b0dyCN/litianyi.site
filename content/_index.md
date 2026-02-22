---
title: "About"
date: 2026-01-05T10:00:00+08:00
---

This site is maintained by an LLM 🙂

## About Me

I'm **Tianyi Li**, a Blockchain Security Engineer at [CertiK](https://www.certik.com/).

Previously, I was a Senior Security Engineer at [Ant Group](https://www.antgroup.com/en), where I designed and implemented high-performance MPC (Secure Multi-Party Computation) systems.

I received my Bachelor's and Master's degrees from the [Wangxuan Institute of Computer Technology (WICT)](https://www.wict.pku.edu.cn/) at [Peking University (PKU)](https://www.pku.edu.cn/). My academic research focused on browser fingerprinting and detection techniques. Beyond academia, I have extensive experience in web security, privacy-enhancing technologies, and program analysis (JavaScript and Linux binaries).

I was also an active member of the CTF team [r3kapig](https://r3kapig.com/) (ID: n0b0dy), focusing primarily on web challenges.

Outside of technology, I am passionate about music and Chinese opera. I have sung **Bass** in the PKU EECS choir for 7 years. You can view our rehearsal history [here](https://eecs129.site/).

## Contact

* **Email:** [contact [AT] litianyi.site](mailto:me@litianyi.site)
* **Github:** [n0b0dyCN](https://github.com/n0b0dyCN)

## Work Experience

#### 2023.5 - Present @ [CertiK](https://www.certik.com/), Blockchain Security Engineer

- **Layer 1 Blockchain Fuzzing:** Conducted security fuzzing for [Massa](https://massa.net/) and [Cosmos](https://cosmos.network/).
- **EVM Emulation Toolkit:** Developed a high-speed, extensible EVM emulation toolkit.
    - Built a transaction emulation & monitoring tool supporting EVM-compatible chains with high performance (10-50ms/tx).
    - Created a no-code smart contract testing tool capable of checking EIP standards (ERC20, ERC721, ERC4626) and detecting attack patterns (e.g., Inflation attacks) against both source code and on-chain contracts.
    - Developed the web user interface for these internal tools.
- **Skylens:** I built [Skylens](https://skylens.certik.com/), a transaction analysis platform featuring:
    - A [bytecode debugger](https://skylens.certik.com/tx/eth/0xbdec39a74e620fc624f90483aff067b17044f81138e6c30038daf7f873159db4?debug_mode=bytecode&instructions_id=0) for low-level transaction inspection.
    - A [storage slot](https://skylens.certik.com/address/eth/0xbea615376d1184f3670a341b70f6f45d9d0fbaad) inspector to query smart contract variables.
- **Tech Stack:** Rust, Solidity, Golang, TypeScript (NextJS).

#### 2021.7 - 2023.5 @ [Ant Group](https://www.antgroup.com/en), Senior Security Engineer

- Developed **TECC**, a distributed and high-performance MPC engine, from scratch.
- Designed and implemented a distributed data analysis framework.
- **Tech Stack:** Rust, Pure C, Python, Intel SGX (Occlum), Java.
- **Outputs:**
    - [TECC White Paper](https://mp.weixin.qq.com/s/Y8zgvyt3QikGvH7sfcjURA)
    - [TECC Presentation at WAIC 2022](https://mp.weixin.qq.com/s/JfUPfQ_crlBuZDZ3zGkuPQ)
    - *See "Patents" section below for related IP.*

## Education

* **2018 - 2021**, [Peking University (PKU)](https://www.pku.edu.cn/)
    - [Wangxuan Institute of Computer Technology (WICT)](https://www.wict.pku.edu.cn/)
    - M.S. in Computer Application Technology
* **2014 - 2018**, [Peking University (PKU)](https://www.pku.edu.cn/)
    - [School of Electronics Engineering and Computer Science (EECS)](https://eecs.pku.edu.cn/)
    - B.S. in Computer Science and Technology

## Research Interests

* Web Security & Privacy (Vulnerabilities, User Tracking, Web Measurement)
* Dynamic and Static Program Analysis (JavaScript, Binary)
* Trusted Execution Environments (Intel SGX)

## Projects

1. [gbdt-rs](https://github.com/mesalock-linux/gbdt-rs): A fast and secure GBDT library, supporting TEEs such as Intel SGX and ARM TrustZone.
2. [Redis Rogue Server](https://github.com/n0b0dyCN/redis-rogue-server): An RCE exploit for Redis <= 5.0.5.

## Publications

\[[Google Scholar](https://scholar.google.com/citations?user=8xv4HxIAAAAJ&hl=en)\]

1. **FPFlow: Detect and Prevent Browser Fingerprinting with Dynamic Taint Analysis** <u>Tianyi Li</u>, Xiaofeng Zheng, Kaiwen Shen, Xinhui Han  
   **[S&P POSTER]** Security & Privacy IEEE, 2021  
   **[CCSAC]** China Cyber Security Annual Conference, 2021  
   [poster abstract](./papers/fpflow-sp21.pdf), [paper](https://link.springer.com/chapter/10.1007/978-981-16-9229-1_4)

2. **From Exposed to Exploited: Drawing the Picture of Industrial Control Systems Security Status in the Internet Age** Yixiong Wu, Jianwei Zhuge, Tingting Yin, <u>Tianyi Li</u>, Junmin Zhu, Guannan Guo, Yue Liu, and Jianju Hu  
   **[ICISSP]** International Conference on Information Systems Security and Privacy, 2021  
   [pdf](./papers/ICScope-icissp21.pdf)

3. **Poster: gbdt-rs: Fast and Trustworthy Gradient Boosting Decision Tree** <u>Tianyi Li</u>, Tongxin Li, Yu Ding, Yulong Zhang, Tao Wei, Xinhui Han  
   **[S&P POSTER]** Security & Privacy IEEE, 2019  
   [pdf](./papers/gbdt-rs-sp19.pdf), [code](https://github.com/mesalock-linux/gbdt-rs)

4. **POSTER: PT-DBG: Automatically anti-debugging bypassing based on Intel Processor Trace** Guancheng Li, Yongheng Chen, <u>Tianyi Li</u>, Tongxin Li, Xinfeng Wu, Chao Zhang, Xinhui Han  
   **[S&P POSTER]** Security & Privacy IEEE, 2018  
   [pdf](./papers/ptdbg-sp18.pdf)

## Patents

1. **Dynamic JavaScript taint analysis:** CN112199274A
2. **Multiparty computation algorithms:** CN114726514A, CN114692060A
3. **Multiparty computation system design:** CN114726512A, CN114726511A, CN114726580A, CN114003962A, CN113992439A, CN113987554A

## Selected CTF Awards

* **14th place**, DEFCON 28 CTF Final (2020)
* **10th place**, DEFCON 27 CTF Final (2019)
* **1st place**, 0CTF/TCTF Final (2019)
* **1st place**, BCTF (2018)
* **1st place**, XCTF Final - HITB Beijing (2018)
* **18th place**, DEFCON 26 CTF Final (2018)
