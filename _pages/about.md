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
My work has been published in top-tier conferences and journals on computer systems, including OSDI, SOSP, FAST, USENIX ATC, EuroSys, ASPLOS, HPCA, DAC, MICRO and ACM TOS. 

<span class="red-text">⭐ We are seeking self-motivated Master, PhD, and undergraduate students with strong programming skills to join our research in computer systems and architectures. If you're interested, feel free to reach out with your CV.</span>

<span class='anchor' id='news'></span>

# 🔥 News
- 🎉 July 2025. Amove (SW/HW codesign of LLM) has been accepted to MICRO'25.
- 🎉 Apr 2025. SpanTrain (AI training system) has been accepted to J-BDR.
- 🎉 Feb 2025. CaMDN (AI accelerator) has been accepted to DAC'25. 
- 🎉 Jan 2025. CoServe (AI inference system) has been accepted to ASPLOS'25.
- 🎉 Nov 2024. Zebra (ZNS SSD RAID) has been accepted to HPCA'25.
- 🎉 August 2024. I will join Beihang University as an associate professor.

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

### - Efficient and Scalable Computer System and Architecture for New Applications (e.g., AI and LLM)
- AI Inference/Serving System: [CoServe](https://dl.acm.org/doi/10.1145/3676641.3715986) (ASPLOS'25), [PipeBoost](https://arxiv.org/abs/2503.17707)
- AI Training System: [DeepCEE](https://arxiv.org/abs/2505.15536v2)
- AI Accelerator: [CaMDN](https://www.arxiv.org/abs/2505.06625) (DAC'25), Amove (MICRO'25)

<span class='anchor' id='pubs'></span>

# 📝 Selected Publications 
(✉: corresponding authors, #: co-first authors)
## 📰 Conference Papers
### [MICRO’25] [Amove: Accelerating LLMs through Mitigating Outliers and Salient Points via Fine-Grained Grouped Vectorized Data Type](https://microarch.org/micro58/)     
Xilong Xie, Liang Wang, Limin Xiao, Meng Han, Lei Liu, Xiangrong Xu, Jinquan Wang, Zhen Song, **Xiaojian Liao**  
Proceedings of the 58th IEEE/ACM International Symposium on Microarchitecture (MICRO 2025), <span class="red-text">(CCF-A)</span>
### [DAC’25] [CaMDN: Enhancing Cache Efficiency for Multi-tenant DNNs on Integrated NPUs](https://www.arxiv.org/abs/2505.06625)    
Tianhao Cai, Liang Wang, Limin Xiao, Meng Han, Zeyu Wang, Lin Sun, **Xiaojian Liao**  
Proceedings of the 61st ACM/IEEE Design Automation Conference (DAC 2025), <span class="red-text">(CCF-A)</span>  
### [ASPLOS’25] [CoServe: Efficient Collaboration-of-Experts (CoE) Model Inference with Limited Memory](https://dl.acm.org/doi/10.1145/3676641.3715986)  
Jiashun Suo, **Xiaojian Liao<sup>✉</sup>**, Limin Xiao<sup>✉</sup>, Li Ruan, Jinquan Wang, Xiao Su, Zhisheng Huo  
Proceedings of the 30th ACM International Conference on Architectural Support for Programming Languages and Operating Systems, Volume 2 (ASPLOS 2025), <span class="red-text">(CCF-A)</span>
### [HPCA’25] [Zebra: Efficient Redundant Array of Zoned Namespace SSDs Enabled by Zone Random Write Area (ZRWA)](https://ieeexplore.ieee.org/document/10946715)  
Tianyang Jiang, Guangyan Zhang, **Xiaojian Liao**, Yuqi Zhou  
Proceedings of the 31st IEEE International Symposium on High-Performance Computer Architecture (HPCA 2025), <span class="red-text">(CCF-A)</span>
### [EuroSys'24] [Volley: Accelerating Write-Read Orders in Disaggregated Storage](https://dl.acm.org/doi/10.1145/3627703.3650090)  
Shaoxun Zeng, **Xiaojian Liao**, Hao Guo, Youyou Lu  
Proceedings of the Nineteenth European Conference on Computer Systems (EuroSys 2024), <span class="red-text">(CCF-A)</span>
### [FAST'24] [TeRM: Extending RDMA-Attached Memory with SSD](https://www.usenix.org/conference/fast24/presentation/yang-zhe)  
Zhe Yang, Qing Wang, **Xiaojian Liao**, Youyou Lu, Keji Huang, Jiwu Shu  
Proceedings of the 22nd USENIX Conference on File and Storage Technologies (FAST 2024), <span class="red-text">(CCF-A)</span>  
<span class="red-text">Invited for fast-tracked publication in ACM Transactions on Storage</span>
### [USENIX ATC'23] [SingularFS: A Billion-Scale Distributed File System Using a Single Metadata Server](https://www.usenix.org/conference/atc23/presentation/guo)  
Hao Guo, Youyou Lu, Wenhao Lv, **Xiaojian Liao**, Shaoxun Zeng, Jiwu Shu  
Proceedings of 2023 USENIX Annual Technical Conference (USENIX ATC 2023), <span class="red-text">(CCF-A)</span>
### [FAST'23] [λ-IO: A Unified IO Stack for Computational Storage](https://www.usenix.org/conference/fast23/presentation/yang-zhe)  
Zhe Yang, Youyou Lu, **Xiaojian Liao**, Youmin Chen, Junru Li, Siyu He, Jiwu Shu  
Proceedings of the 21st USENIX Conference on File and Storage Technologies (FAST 2023), <span class="red-text">(CCF-A)</span>
### [EuroSys'23] [RIO: Order-Preserving and CPU-Efficient Remote Storage Access](https://dl.acm.org/doi/abs/10.1145/3552326.3567495)  
**Xiaojian Liao**, Zhe Yang, Jiwu Shu  
Proceedings of the 18th European Conference on Computer Systems (EuroSys 2023), <span class="red-text">(CCF-A)</span>
### [SOSP'21] [Crash Consistent Non-Volatile Memory Express](https://dl.acm.org/doi/10.1145/3477132.3483592)  
**Xiaojian Liao**, Youyou Lu, Zhe Yang, Jiwu Shu  
Proceedings of the 28th ACM Symposium on Operating Systems Principles (SOSP 2021), <span class="red-text">(CCF-A)</span>
### [USENIX ATC'21] [Max: A Multicore-Accelerated File System for Flash Storage](https://www.usenix.org/conference/atc21/presentation/liao)  
**Xiaojian Liao**, Youyou Lu, Erci Xu, Jiwu Shu  
Proceedings of 2021 USENIX Annual Technical Conference (USENIX ATC 2021), <span class="red-text">(CCF-A)</span>
### [OSDI'20] [Write Dependency Disentanglement with HORAE](https://www.usenix.org/conference/osdi20/presentation/liao)  
**Xiaojian Liao**, Youyou Lu, Erci Xu, Jiwu Shu  
Proceedings of the 14th USENIX Symposium on Operating Systems Design and Implementation (OSDI 2020), <span class="red-text">(CCF-A)</span>

## 📖 Journal Papers
### [大数据] [SpanTrain: A Cross-Domain Distributed Model Training System for Cloud-Edge-End Heterogeneous Devices](https://www.j-bigdataresearch.com.cn/zh/article/doi/10.11959/j.issn.2096-0271.2025040/)  
Jinquan Wang, Xuzhao Liu, **Xiaojian Liao<sup>✉</sup>**, Limin Xiao<sup>✉</sup>, Zhisheng Huo, Jiashun Suo, Yuntong Li, Runnan Shen, Xilong Xie, Xicheng Tang  
Journal of BIG DATA RESEARCH (大数据 in Chinese), 2025, (CCF-T2)  
### [ACM TOS'25] [Efficiently Enlarging RDMA-Attached Memory with SSD](https://dl.acm.org/doi/10.1145/3700772)  
Zhe Yang, Qing Wang, **Xiaojian Liao**, Youyou Lu, Keji Huang, Jiwu Shu  
ACM Transactions on Storage (ACM TOS 2025), Volume 21, Issue 2, <span class="red-text">(CCF-A)</span>, <span class="red-text">Fast-Tracked</span>
### [ACM TOS'23] [Efficient Crash Consistency for NVMe over PCIe and RDMA](https://dl.acm.org/doi/full/10.1145/3568428)  
**Xiaojian Liao**, Youyou Lu, Zhe Yang, Jiwu Shu  
ACM Transactions on Storage (ACM TOS 2023), Volume 19, Issue 1, <span class="red-text">(CCF-A)</span>
### [中国科学: 信息科学] [Progress on Storage Systems for Disaggregated Data Centers](http://scis.scichina.com/cn/2023/SSI-2023-0034.pdf)  
Jiwu Shu, Youmin Chen, Qing Wang, Jing Wang, Junru Li, **Xiaojian Liao**  
SCIENTIA SINICA Informationis (中国科学: 信息科学, In Chinese), 2023, (CCF-T1)
### [计算机研究与发展] [A Low-Latency Storage Engine with Low CPU Overhead](https://crad.ict.ac.cn/article/doi/10.7544/issn1000-1239.20210574)  
**Xiaojian Liao**, Zhe Yang, Hongzhang Yang, Yaofeng Tu, Jiwu Shu  
Journal of Computer Research and Development (计算机研究与发展, in Chinese), 2023, (CCF-T1)

## ✍️ Preprint
### [PipeBoost: Resilient Pipelined Architecture for Fast Serverless LLM Scaling](https://arxiv.org/abs/2503.17707)  
Chongpeng Liu, **Xiaojian Liao<sup>✉</sup>**, Hancheng Liu, Limin Xiao, Jianxin Li<sup>✉</sup>
### [DeepCEE: Efficient Cross-Region Model Distributed Training System under Heterogeneous GPUs and Networks](https://arxiv.org/abs/2505.15536v2)  
Jinquan Wang<sup>#</sup>, **Xiaojian Liao<sup>#</sup>**, Xuzhao Liu, Jiashun Suo, Zhisheng Huo, Chenhao Zhang, Xiangrong Xu, Runnan Shen, Xilong Xie, Limin Xiao

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
- 2024-2025, Journal Reviewer of IEEE Transactions on Computers
- 2024, Program committee of the 26th ACM SIGOPS ChinaSys workshop 
- 2023, Program committee of the 10th ACM Eurosys PaPoc workshop
- 2022, Journal reviewer of IEEE Transactions on Cloud Computing
