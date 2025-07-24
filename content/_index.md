---
title: "About"
date: 2021-02-20T20:27:14+08:00
---

## About Me

I'm Tianyi Li, a blockchain security engineer at [CertiK](https://www.certik.com/).

Previous to that, I was a senior security engineer at [Antgroup](https://www.antgroup.com/en), designed and implemented high performance MPC computation system.

I received my Bachelor and Master degree at [Wangxuan Institute of Computer Technology (WICT)](https://www.wict.pku.edu.cn/) of [Peking University (PKU)](https://www.pku.edu.cn/).
My research includes browser fingerprinting and it's detection techniques.
I also worked on web security, privacy enhancing technologies and program (JavaScript and linux binary) analysis.
I was a member of CTF team [r3kapig](https://r3kapig.com/) (ID: n0b0dy), and I mainly focus on web challenges.

I’m interested in music.
I have participated in the rehearsal of the PKU EECS chorus competition for 7 years ([link](https://eecs129.site/)), and I sing as Base in the choir.
I’m also interested in Chinese opera.

## Contact

* Email: [contact \[AT\] litianyi.site](mailto:me@litianyi.site)
* Github: [https://github.com/n0b0dyCN](https://github.com/n0b0dyCN)

## Work Experience

#### 2023.5 - present @ [CertiK](https://www.certik.com/), Blockchain Security Engineer

- Layer 1 blockchain fuzzing ([Massa](https://massa.net/), [Cosmos](https://cosmos.network/)).
- EVM emulation toolkit development focusing on speed and extensibility.
    - Building a transaction emulation & monitoring tool upon the toolkit supporting EVM compatable chain with high performance (10-50ms/tx).
    - Building a no-code testing tool for smart contract upon the toolkit, write rules for EIP standard (ERC20, ERC721, ERC4626, etc.) and attack patterns (e.g., Inflation attack), support testing against source code and on-chain contracts.
    - Build web user interface for the tools.
- I build [Skylens](https://skylens.certik.com/) for transaction analysis with some interesting features like:
    - A [bytecode debugger](https://skylens.certik.com/tx/eth/0xbdec39a74e620fc624f90483aff067b17044f81138e6c30038daf7f873159db4?debug_mode=bytecode&instructions_id=0) to debug transaction at bytecode level.
    - A [storage slot](https://skylens.certik.com/address/eth/0xbea615376d1184f3670a341b70f6f45d9d0fbaad) inspecting tool to query variables in smart contract.
- Tech Stack: Rust, Solidity, Golang

#### 2021.7 - 2023.5 @ [Antgroup](https://www.antgroup.com/en), Senior Security Engineer

- Develop **distributed** and **fast** MPC engine (TECC) from scratch
- Design & implement distributed data analysis framework from scratch
- Tech Stack: Rust, PURE C, Python, Intel SGX with Occlum, a little bit Java
- Resources:
    - Patents involved (first author): CN114726514A, CN114692060A
    - Patents involved (other): CN114726512A, CN114726511A, CN114726580A, CN114003962A, CN113992439A, CN113987554A
    - Public available resources: [TECC white paper](https://mp.weixin.qq.com/s/Y8zgvyt3QikGvH7sfcjURA), [TECC in WAIC 2022](https://mp.weixin.qq.com/s/JfUPfQ_crlBuZDZ3zGkuPQ)


## Education

* 2018 - 2021, [Peking University (PKU)](https://www.pku.edu.cn/)
    - [Wangxuan Institute of Computer Technology (WICT)](https://www.wict.pku.edu.cn/)
    - Master of Science in Computer Application Technology
* 2014 - 2018, [Peking University (PKU)](https://www.pku.edu.cn/)
    - [School of Electronics Engineering and Computer Science (EECS)](https://eecs.pku.edu.cn/)
    - Bachelor of Science in Computer Science and Technology

## Research Interest

* Web Security & Privacy (Vulnerabilities, User Tracking, Web/Internet Measurement)
* Dynamic and Static Program Analysis (JavaScript, Binary)
* Trusted Execution Environment (Intel SGX)

## Projects

1. [gbdt-rs](https://github.com/mesalock-linux/gbdt-rs): A fast and secure GBDT library, supporting TEEs such as Intel SGX and ARM TrustZone
1. [Redis Rogue Server](https://github.com/n0b0dyCN/redis-rogue-server): Redis <= 5.0.5 RCE exploit

## Publications

\[[Google Scholar](https://scholar.google.com/citations?user=8xv4HxIAAAAJ&hl=en)\]

1. **FPFlow: Detect and Prevent Browser Fingerprinting with Dynamic Taint Analysis**</br>
<u>Tianyi Li</u>, Xiaofeng Zheng, Kaiwen Shen, Xinhui Han</br>
**[S&P POSTER]** Security & Privacy IEEE, 2021</br>
**[CCSAC]** China Cyber Security Annual Conference, 2021</br>
**[Patent]** 基于V8引擎的JavaScript动态污点跟踪方法及电子装置 [CN112199274A]</br>
[poster abstract](./papers/fpflow-sp21.pdf), [paper](https://link.springer.com/chapter/10.1007/978-981-16-9229-1_4)
1. **From Exposed to Exploited: Drawing the Picture of Industrial Control Systems Security Status in the Internet Age**</br>
Yixiong Wu, Jianwei Zhuge, Tingting Yin, <u>Tianyi Li</u>, Junmin Zhu, Guannan Guo, Yue Liu and Jianju Hu</br>
**[ICISSP]** International Conference on Information Systems Security and Privacy, 2021</br>
[pdf](./papers/ICScope-icissp21.pdf)
1. **Poster: gbdt-rs: Fast and Trustworthy Gradient Boosting Decision Tree**</br>
<u>Tianyi Li</u>, Tongxin Li, Yu Ding, Yulong Zhang, Tao Wei, Xinhui Han</br>
**[S&P POSTER]** Security & Privacy IEEE, 2019</br>
[pdf](./papers/gbdt-rs-sp19.pdf), [code](https://github.com/mesalock-linux/gbdt-rs)
1. **POSTER: PT-DBG: Automatically anti-debugging bypassing based on Intel Processor Trace**</br>
Guancheng Li, Yongheng Chen, <u>Tianyi Li</u>, Tongxin Li, Xinfeng Wu, Chao Zhang, Xinhui Han</br>
**[S&P POSTER]** Security & Privacy IEEE, 2018</br>
[pdf](./papers/ptdbg-sp18.pdf)

## Patents

1. Dynamic JavaScript taint analysis: CN112199274A
2. Multiparty computation algorithms: CN114726514A, CN114692060A
3. Multiparty computation system design: CN114726512A, CN114726511A, CN114726580A, CN114003962A, CN113992439A, CN113987554A

## Selected CTF Awards

* DEFCON 28 CTF Final , 2020 14th place
* DEFCON 27 CTF Final , 2019 10th place
* 0CTF/TCTF 2019 Final, 1st place
* BCTF 2018, 1st place
* XCTF 2018 Final - HITB Beijing, 1st place
* DEFCON 26 CTF Final, 18th place
