---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

I am an associate professor in the School of Computer Science and Engineering, [Beihang University (BUAA)](https://ev.buaa.edu.cn/). 
I was a postdoc researcher in the Department of Computer Science and Technology, Tsinghua University. 
I received my PhD degree from Tsinghua University in 2022 (advised by Professor [Jiwu Shu](https://storage.cs.tsinghua.edu.cn/~jiwu-shu/) and [Youyou Lu](https://storage.cs.tsinghua.edu.cn/~lu/)), and Bachelor degree from [Huazhong University of Science and Technology (HUST)](https://english.hust.edu.cn/) in 2017. 

My research interests are primarily in **storage systems and AI systems**, focusing on enhancing their performance and reliability.
My work has been published in top-tier conferences and journals on computer systems, including OSDI, SOSP, FAST, USENIX ATC, EuroSys, ASPLOS, HPCA and ACM TOS. 

<font color="red">⭐ We are seeking self-motivated Master, PhD, and undergraduate students with strong programming skills to join our research in computer systems and architectures. If you're interested, feel free to reach out with your CV.</font>

<span class='anchor' id='news'></span>

# 🔥 News
- 🆕 Jan, 2025. CoServe (AI inference system) has been accepted by ASPLOS'25.
- 🆕 Nov, 2024. Zebra (ZNS SSD RAID) has been accepted by HPCA'25.
- 🆕 August, 2024. I will join Beihang University as an associate professor.

<span class='anchor' id='research'></span>

# 🔍 Research Topics

### - I/O Stack and File System on Modern/Future Storage Devices (e.g., NVMe and CXL SSD)
- Consistency and Reliability: [HORAE](https://www.usenix.org/conference/osdi20/presentation/liao) (OSDI'20), [ccNVMe](https://dl.acm.org/doi/10.1145/3477132.3483592) (SOSP'21)
- Concurrency and Scalability: [MAX](https://www.usenix.org/conference/atc21/presentation/liao) (USENIX ATC'21)
- Computational Storage (Smart SSD): [λ-IO](https://www.usenix.org/conference/fast23/presentation/yang-zhe) (FAST'23)

### - Distributed and Networked Storage System on Fast Network Devices (e.g., RDMA NIC and DPU)
- Disaggregated Storage (NVMe-oF): [RIO](https://dl.acm.org/doi/abs/10.1145/3552326.3567495) (EuroSys'23), [ccNVMe-oF](https://dl.acm.org/doi/full/10.1145/3568428) (ACM TOS), [Volley](https://dl.acm.org/doi/10.1145/3627703.3650090) (EuroSys'24)
- Distributed File System: [SuperFS](https://io500.org/list/sc22/ten?sort=io500_md&direction=desc) (#1 in the IO500 10-node Metadata Challenge, SC'22), [SingularFS](https://www.usenix.org/conference/atc23/presentation/guo) (USNNIX ATC'23)
- RDMA-based Storage: [TeRM](https://www.usenix.org/conference/fast24/presentation/yang-zhe) (FAST'24, ACM TOS)
<span class='anchor' id='pubs'></span>

### - Efficient and Scalable Operating and Distributed System for New Applications (e.g., AI and LLM)
- AI Inference/Serving: CoServe (ASPLOS'25)

# 📝 Selected Publications
## 📰 Conference Papers
- CoServe: Efficient Collaboration-of-Experts (CoE) Model Inference with Limited Memory, **ASPLOS 2025** \\
Jiashun Suo, **Xiaojian Liao<sup>*</sup>**, Limin Xiao<sup>*</sup>, Li Ruan, Jinquan Wang, Xiao Su, Zhisheng Huo
- Zebra: Efficient Redundant Array of Zoned Namespace SSDs Enabled by Zone Random Write Area (ZRWA), **HPCA 2025** \\
Tianyang Jiang, Guangyan Zhang, **Xiaojian Liao**, Yuqi Zhou
- [Volley: Accelerating Write-Read Orders in Disaggregated Storage](https://dl.acm.org/doi/10.1145/3627703.3650090), **EuroSys 2024**  \\
Shaoxun Zeng, **Xiaojian Liao**, Hao Guo, Youyou Lu
- [TeRM: Extending RDMA-Attached Memory with SSD](https://www.usenix.org/conference/fast24/presentation/yang-zhe), **FAST 2024** \\
Zhe Yang, Qing Wang, **Xiaojian Liao**, Youyou Lu, Keji Huang, Jiwu Shu
- [SingularFS: A Billion-Scale Distributed File System Using a Single Metadata Server](https://www.usenix.org/conference/atc23/presentation/guo), **USENIX ATC 2023** \\
Hao Guo, Youyou Lu, Wenhao Lv, **Xiaojian Liao**, Shaoxun Zeng, Jiwu Shu
- [λ-IO: A Unified IO Stack for Computational Storage](https://www.usenix.org/conference/fast23/presentation/yang-zhe), **FAST 2023** \\
Zhe Yang, Youyou Lu, **Xiaojian Liao**, Youmin Chen, Junru Li, Siyu He, Jiwu Shu
- [RIO: Order-Preserving and CPU-Efficient Remote Storage Access](https://dl.acm.org/doi/abs/10.1145/3552326.3567495), **EuroSys 2023** \\
**Xiaojian Liao**, Zhe Yang, Jiwu Shu
- [Crash Consistent Non-Volatile Memory Express](https://dl.acm.org/doi/10.1145/3477132.3483592), **SOSP 2021** \\
**Xiaojian Liao**, Youyou Lu, Zhe Yang, Jiwu Shu
- [Max: A Multicore-Accelerated File System for Flash Storage](https://www.usenix.org/conference/atc21/presentation/liao), **USENIX ATC 2021** \\
**Xiaojian Liao**, Youyou Lu, Erci Xu, Jiwu Shu
- [Write Dependency Disentanglement with HORAE](https://www.usenix.org/conference/osdi20/presentation/liao), **OSDI 2020** \\
**Xiaojian Liao**, Youyou Lu, Erci Xu, Jiwu Shu

## 📖 Journal Papers
- [Efficiently Enlarging RDMA-Attached Memory with SSD](https://dl.acm.org/doi/10.1145/3700772), **ACM TOS 2024** \\
Zhe Yang, Qing Wang, **Xiaojian Liao**, Youyou Lu, Keji Huang, Jiwu Shu
- [Efficient Crash Consistency for NVMe over PCIe and RDMA](https://dl.acm.org/doi/full/10.1145/3568428), **ACM TOS 2023** \\
**Xiaojian Liao**, Youyou Lu, Zhe Yang, Jiwu Shu
- [Progress on Storage Systems for Disaggregated Data Centers](http://scis.scichina.com/cn/2023/SSI-2023-0034.pdf), SCIENTIA SINICA Informationis (中国科学: 信息科学) (In Chinese) \\
Jiwu Shu, Youmin Chen, Qing Wang, Jing Wang, Junru Li, **Xiaojian liao**
- [A Low-Latency Storage Engine with Low CPU Overhead](https://crad.ict.ac.cn/article/doi/10.7544/issn1000-1239.20210574), Journal of Computer Research and Development (计算机研究与发展) (in Chinese) \\
**Xiaojian Liao**, Zhe Yang, Hongzhang Yang, Yaofeng Tu, Jiwu Shu

<span class='anchor' id='awards'></span>

# 🏅 Selected Honors & Awards

- 2022, SuperFS ranked #1 in the IO500 10-node Metadata Challenge, SC'22
- 2022, ACM SIGOPS ChinaSys Doctoral Dissertation Award
- 2022, Shuimu Tsinghua Scholar (清华大学水木学者)
- 2022, Distinguished Doctoral Graduate of Tsinghua University (清华大学优秀博士毕业生, 5 PhDs in CS department)
- 2022, Distinguished Doctoral Dissertation Award of Tsinghua University (清华大学优秀博士学位论文, 9 PhDs in CS department)
- 2021, First Prize of Shenzhen Science and Technology Improvement Award （深圳市科技进步奖一等奖）
- 2021, Zhong Shimo Scholarship (清华计算机系钟士模奖学金, the highest honour of CS students of Tsinghua, 4 postgraduate students)
- 2021, First Prize of 1984 Innovation Scholarship (only 1 project was awarded)
- 2020, ByteDance Scholars Program (10 students nationwide were selected)

<span class='anchor' id='services'></span>

# 🕑 Professional Services

- 2024, Program committee of the 26th ACM SIGOPS ChinaSys workshop 
- 2023, Program committee of the 10th ACM Eurosys PaPoc workshop
- 2022, Journal reviewer of IEEE transactions on Cloud Computing
