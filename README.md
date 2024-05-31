# Awesome-LVLM-Attack [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A **continual** collection of papers related to Attacks on Large-Vision-Language-Models (LVLMs).

Large vision-language models (LVLMs) have achieved significant success and demonstrated promising capabilities in various multimodal downstream tasks.
Despite their remarkable capabilities, the increased complexity and deployment of LVLMs have also exposed them to various security threats and vulnerabilities, making the study of attacks on these models a critical area of research.

Here, we've summarized existing LVLM Attack methods in our survey paper👍.


> If you find some important work missed, it would be super helpful to let me know (`dzliu@stu.pku.edu.cn`). Thanks!

> If you find our survey useful for your research, please consider citing:

```
@article{liu2024attack,
  title={A Survey of Attacks on Large Vision-Language Models: Resources, Recent Advances, and Future Trends},
  author={Liu, Daizong and Yang, Mingyu and Qu, Xiaoye and Hu, Wei},
  journal={arXiv preprint arXiv},
  year={2024}
}
```

**Table of Contents**
- [Adversarial Attacks](#Adversarial-Attack)
- [Jailbreack Attacks](#Jailbreack-Attack)
- [Prompt Injection](#Prompt-Injection)
- [Data Poisoning](#Data-Poisoning)
---

## Adversarial-Attack
* **On the Adversarial Robustness of Multi-Modal Foundation Models** | 
  * Christian Schlarmann, Matthias Hein
  * University of Tubingen
  * [ICCVworkshop2023] https://openaccess.thecvf.com/content/ICCV2023W/AROW/papers/Schlarmann_On_the_Adversarial_Robustness_of_Multi-Modal_Foundation_Models_ICCVW_2023_paper.pdf
* **On Evaluating Adversarial Robustness of Large Vision-Language Models** | [Github](https://github.com/yunqing-me/AttackVLM)
  * Yunqing Zhao, Tianyu Pang, Chao Du, Xiao Yang, Chongxuan Li, Ngai-Man Cheung, Min Lin
  * Singapore University of Technology and Design, Sea AI Lab, Tsinghua University, Renmin University of China
  * [NeurIPs2023] https://arxiv.org/abs/2305.16934
* **VLATTACK: Multimodal Adversarial Attacks on Vision-Language Tasks via Pre-trained Models** | [Github](https://github.com/ericyinyzy/VLAttack)
  * Ziyi Yin, Muchao Ye, Tianrong Zhang, Tianyu Du, Jinguo Zhu, Han Liu, Jinghui Chen, Ting Wang, Fenglong Ma
  * The Pennsylvania State University, Zhejiang University, Xi’an Jiaotong University, Dalian University of Technology, Stony Brook University
  * [NeurIPs2023] [https://arxiv.org/abs/2312.03777](https://arxiv.org/abs/2310.04655)
* **Adversarial Illusions in Multi-Modal Embeddings** | [Github](https://github.com/ebagdasa/adversarial_illusions)
  * Tingwei Zhang, Rishi Jha, Eugene Bagdasaryan, Vitaly Shmatikov
  * Cornell University, Cornell Tech
  * [Arxiv2023] https://arxiv.org/abs/2308.11804
* **Image Hijacks: Adversarial Images can Control Generative Models at Runtime** | [Github](https://github.com/euanong/image-hijacks)
  * Luke Bailey, Euan Ong, Stuart Russell, Scott Emmons
  * UC Berkeley, Harvard University, University of Cambridge
  * [Arxiv2023] https://arxiv.org/abs/2309.00236
* **How Robust is Google's Bard to Adversarial Image Attacks?** | [Github](https://github.com/thu-ml/Attack-Bard)
  * Yinpeng Dong, Huanran Chen, Jiawei Chen, Zhengwei Fang, Xiao Yang, Yichi Zhang, Yu Tian, Hang Su, Jun Zhu
  * Tsinghua University, RealAI
  * [Arxiv2023] https://arxiv.org/abs/2309.11751
* **Misusing Tools in Large Language Models With Visual Adversarial Examples** | 
  * Xiaohan Fu, Zihan Wang, Shuheng Li, Rajesh K. Gupta, Niloofar Mireshghallah, Taylor Berg-Kirkpatrick, Earlence Fernandes
  * University of California San Diego, University of Washington
  * [Arxiv2023] https://arxiv.org/abs/2310.03185
* **How Many Unicorns Are in This Image? A Safety Evaluation Benchmark for Vision LLMs** | [Github](https://github.com/UCSC-VLAA/vllm-safety-benchmark)
  * Haoqin Tu, Chenhang Cui, Zijun Wang, Yiyang Zhou, Bingchen Zhao, Junlin Han, Wangchunshu Zhou, Huaxiu Yao, Cihang Xie
  * UC Santa Cruz, UNC-Chapel Hill, University of Edinburgh, University of Oxford, AIWaves Inc.
  * [Arxiv2023] https://arxiv.org/abs/2311.16101
* **On the Robustness of Large Multimodal Models Against Image Adversarial Attacks** | 
  * Xuanming Cui, Alejandro Aparcedo, Young Kyun Jang, Ser-Nam Lim
  * University of Central Florida
  * [Arxiv2023] https://arxiv.org/abs/2312.03777
* **InstructTA: Instruction-Tuned Targeted Attack for Large Vision-Language Models** | 
  * Xunguang Wang, Zhenlan Ji, Pingchuan Ma, Zongjie Li, Shuai Wang
  * The Hong Kong University of Science and Technology
  * [Arxiv2023] https://arxiv.org/abs/2312.01886
* **OT-Attack: Enhancing Adversarial Transferability of Vision-Language Models via Optimal Transport Optimization** | 
  * Dongchen Han, Xiaojun Jia, Yang Bai, Jindong Gu, Yang Liu, Xiaochun Cao
  *  Sun Yat-sen University, Nanyang Technological University, Tsinghua University, University of Oxford
  * [Arxiv2023] https://arxiv.org/abs/2312.04403
* **An Image Is Worth 1000 Lies: Transferability of Adversarial Images across Prompts on Vision-Language Models** | [Github](https://github.com/Haochen-Luo/CroPA)
  * Haochen Luo, Jindong Gu, Fengyuan Liu, Philip Torr
  * University of Oxford
  * [ICLR2024] https://arxiv.org/abs/2403.09766
* **Inducing High Energy-Latency of Large Vision-Language Models with Verbose Images** | [Github](https://github.com/KuofengGao/Verbose_Images)
  * Kuofeng Gao, Yang Bai, Jindong Gu, Shu-Tao Xia, Philip Torr, Zhifeng Li, Wei Liu
  * Tsinghua University, Tencent Technology (Beijing),  University of Oxford, Tencent Data Platform, Peng Cheng Laboratory
  * [ICLR2024] https://arxiv.org/abs/2401.11170
* **Adversarial Robustness for Visual Grounding of Multimodal Large Language Models** | 
  * Kuofeng Gao, Yang Bai, Jiawang Bai, Yong Yang, Shu-Tao Xia
  * Tsinghua University, Tencent Security Platform, Peng Cheng Laboratory
  * [ICLRworkshop2024] https://arxiv.org/abs/2405.09981
* **Transferable Multimodal Attack on Vision-Language Pre-training Models** | 
  * Haodi Wang, Kai Dong, Zhilei Zhu, Haotong Qin, Aishan Liu, Xiaolin Fang, Jiakai Wang, Xianglong Liu
  * Southeast University, Data Space Research Institute of Hefei Comprehensive National Science Centre, Beihang University, Southeast University, Zhongguancun Laboratory
  * [S&P2024] https://www.computer.org/csdl/proceedings-article/sp/2024/313000a102/1Ub239H4xyg
* **On the Safety Concerns of Deploying LLMs/VLMs in Robotics: Highlighting the Risks and Vulnerabilities** | 
  * Xiyang Wu, Ruiqi Xian, Tianrui Guan, Jing Liang, Souradip Chakraborty, Fuxiao Liu, Brian Sadler, Dinesh Manocha, Amrit Singh Bedi
  * University of Maryland, Army Research Laboratory, University of Central Florida
  * [Arxiv2024] https://arxiv.org/abs/2402.10340
* **The Wolf Within: Covert Injection of Malice into MLLM Societies via an MLLM Operative** | [Github](https://github.com/ChengshuaiZhao0/The-Wolf-Within)
  * Zhen Tan, Chengshuai Zhao, Raha Moraffah, Yifan Li, Yu Kong, Tianlong Chen, Huan Liu
  * Arizona State University, Michigan State University, Harvard University
  * [Arxiv2024] https://arxiv.org/abs/2402.14859
* **Stop Reasoning! When Multimodal LLMs with Chain-of-Thought Reasoning Meets Adversarial Images** | 
  * Zefeng Wang, Zhen Han, Shuo Chen, Fan Xue, Zifeng Ding, Xun Xiao, Volker Tresp, Philip Torr, Jindong Gu
  * Technical University of Munich, Ludwig Maximilian University of Munich, Huawei Munich Research Center, University of Oxford
  * [Arxiv2024] https://arxiv.org/abs/2402.14899
* **AVIBench: Towards Evaluating the Robustness of Large Vision-Language Model on Adversarial Visual-Instructions** | 
  * Hao Zhang, Wenqi Shao, Hong Liu, Yongqiang Ma, Ping Luo, Yu Qiao, Kaipeng Zhang
  * Xi’an Jiaotong University, Shanghai Artificial Intelligence Laboratory, Osaka University
  * [Arxiv2024] https://arxiv.org/abs/2403.09346
* **Efficiently Adversarial Examples Generation for Visual-Language Models under Targeted Transfer Scenarios using Diffusion Models** | 
  * Qi Guo, Shanmin Pang, Xiaojun Jia, Qing Guo
  * Xi’an Jiaotong University, Nanyang Technological University, Center for Frontier AI Research
  * [Arxiv2024] https://arxiv.org/abs/2404.10335

## Jailbreak-Attack


## Prompt-Injection


## Data-Poisoning
