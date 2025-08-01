# Awesome-LVLM-Attack [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A **continual** collection of papers related to Attacks on Large-Vision-Language-Models (LVLMs).

Large vision-language models (LVLMs) have achieved significant success and demonstrated promising capabilities in various multimodal downstream tasks.
Despite their remarkable capabilities, the increased complexity and deployment of LVLMs have also exposed them to various security threats and vulnerabilities, making the study of attacks on these models a critical area of research.

Here, we've summarized existing LVLM Attack methods in our survey paper👍.

[A Survey of Attacks on Large Vision-Language Models: Resources, Advances, and Future Trends](https://arxiv.org/abs/2407.07403)

> If you find some important work missed, it would be super helpful to let me know (`dzliu@stu.pku.edu.cn`). Thanks!

> If you find our survey useful for your research, please consider citing:

```
@article{liu2024attack,
  title={A Survey of Attacks on Large Vision-Language Models: Resources, Advances, and Future Trends},
  author={Liu, Daizong and Yang, Mingyu and Qu, Xiaoye and Zhou, Pan and Cheng, Yu and Hu, Wei},
  journal={arXiv preprint arXiv:2407.07403},
  year={2024}
}
```

**Table of Contents**
- [Adversarial Attacks](#Adversarial-Attack)
- [Jailbreak Attacks](#Jailbreak-Attack)
- [Prompt Injection](#Prompt-Injection)
- [Data Poisoning](#Data-Poisoning)
- [Special Attacks For LVLM Applications](#Special-Attacks-For-LVLM-Applications)
- [Benchmarks](#Benchmarks)

<div align=center><img src="./img/four_attacks.png" width="90%" height="90%" /></div>

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
* **Adversarial Attacks on Multimodal Agents** | 
  * Chen Henry Wu, Jing Yu Koh, Ruslan Salakhutdinov, Daniel Fried, Aditi Raghunathan
  * Carnegie Mellon University
  * [Arxiv2024] https://arxiv.org/abs/2406.12814
* **Refusing Safe Prompts for Multi-modal Large Language Models** | 
  * Zedian Shao, Hongbin Liu, Yuepeng Hu, Neil Zhenqiang Gong
  * Duke University
  * [Arxiv2024] https://arxiv.org//abs/2407.09050
* **Manipulation Facing Threats: Evaluating Physical Vulnerabilities in End-to-End Vision Language Action Models** | 
  * Hao Cheng, Erjia Xiao, Chengyuan Yu, Zhao Yao, Jiahang Cao, Qiang Zhang, Jiaxu Wang, Mengshu Sun, Kaidi Xu, Jindong Gu, Renjing Xu
  * The Hong Kong University of Science and Technology, University of Oxford, Hohai University, Hunan University, Drexel University, Beijing University of Technology
  * [Arxiv2024] https://arxiv.org/abs/2409.13174
* **AnyAttack: Towards Large-scale Self-supervised Generation of Targeted Adversarial Examples for Vision-Language Models** | [Github](https://github.com/jiamingzhang94/AnyAttack) 
  * Jiaming Zhang, Junhong Ye, Xingjun Ma, Yige Li, Yunfan Yang, Jitao Sang, Dit-Yan Yeung
  * Hong Kong University of Science and Technology, Beijing Jiaotong University, Fudan University, Singapore Management University
  * [Arxiv2024] https://arxiv.org//abs/2410.05346
* **Doubly-Universal Adversarial Perturbations: Deceiving Vision-Language Models Across Both Images and Text with a Single Perturbation** | 
  * Hee-Seon Kim, Minbeom Kim, Changick Kim
  * Korea Advanced Institute of Science and Technology
  * [Arxiv2024] https://arxiv.org/abs/2412.08108
* **On the Robustness of Large Multimodal Models Against Image Adversarial Attacks** |
  * Xuanming Cui, Alejandro Aparcedo, Young Kyun Jang, Ser-Nam Lim
  * University of Central Florida
  * [CVPR2024] https://openaccess.thecvf.com/content/CVPR2024/papers/Cui_On_the_Robustness_of_Large_Multimodal_Models_Against_Image_Adversarial_CVPR_2024_paper.pdf
* **Exploring the Transferability of Visual Prompting for Multimodal Large Language Models** | [Github](https://github.com/zycheiheihei/Transferable-Visual-Prompting) 
  * Yichi Zhang, Yinpeng Dong, Siyuan Zhan, Tianzan Min, Hang Su, Jun Zhu
  * Tsinghua University, RealAI, Pazhou Laboratory (Huangpu)
  * [CVPR2024] https://openaccess.thecvf.com/content/CVPR2024/papers/Zhang_Exploring_the_Transferability_of_Visual_Prompting_for_Multimodal_Large_Language_CVPR_2024_paper.pdf
* **Break the Visual Perception: Adversarial Attacks Targeting Encoded Visual Tokens of Large Vision-Language Models** | 
  * Yubo Wang, Chaohu Liu, Yanqiu Qu, Haoyu Cao, Deqiang Jiang, Linli Xu
  * University of Science and Technology of China, Tencent YouTu Lab
  * [ACMMM2024] https://arxiv.org/abs/2410.06699
* **Pandora's Box: Towards Building Universal Attackers against Real-World Large Vision-Language Models** | 
  * Daizong Liu, Mingyu Yang, Xiaoye Qu, Pan Zhou, Xiang Fang, Keke Tang, Yao Wan, Lichao Sun
  * Peking University, Huazhong University of Science and Technology, Nanyang Technological University, Guangzhou University, Lehigh University
  * [NeurIPS2024] https://openreview.net/forum?id=gDpWYpocE1
* **Image-based Multimodal Models as Intruders: Transferable Multimodal Attacks on Video-based MLLMs** | 
  * Linhao Huang, Xue Jiang, Zhiqiang Wang, Wentao Mo, Xi Xiao, Bo Han, Yongjie Yin, Feng Zheng
  * Tsinghua University, Southern University of Science and Technology, Hong Kong Baptist University, Hong Kong University of Science and Technology, China Electronics Corporation
  * [Arxiv2025] https://arxiv.org/abs/2501.01042
* **Effective Black-Box Multi-Faceted Attacks Breach Vision Large Language Model Guardrails** | 
  * Yijun Yang, Lichao Wang, Xiao Yang, Lanqing Hong, Jun Zhu
  * Tsinghua University, Huawei Noah’s Ark Lab
  * [Arxiv2025] https://arxiv.org/abs/2502.05772
* **Universal Adversarial Attack on Aligned Multimodal LLMs** | 
  * Temurbek Rahmatullaev, Polina Druzhinina, Matvey Mikhalchuk, Andrey Kuznetsov, Anton Razzhigaev
  * n/a
  * [Arxiv2025] https://arxiv.org/abs/2502.07987
* **Improving Adversarial Transferability in MLLMs via Dynamic Vision-Language Alignment Attack** |  #
  * Chenhe Gu, Jindong Gu, Andong Hua, Yao Qin
  * University of California, University of Oxford
  * [Arxiv2025] https://arxiv.org/abs/2502.19672
* **Safeguarding Vision-Language Models: Mitigating Vulnerabilities to Gaussian Noise in Perturbation-based Attacks** |  #
  * Jiawei Wang, Yushen Zuo, Yuanjun Chai, Zhendong Liu, Yichen Fu, Yichun Feng, Kin-man Lam
  * University of Science and Technology of China, The Hong Kong Polytechnic University, University of Washington, Nanjing University, Stanford University, University of the Chinese Academy of Sciences
  * [Arxiv2025] https://arxiv.org/abs/2504.01308
* **Manipulating Multimodal Agents via Cross-Modal Prompt Injection** |  #
  * Le Wang, Zonghao Ying, Tianyuan Zhang, Siyuan Liang, Shengshan Hu, Mingchuan Zhang, Aishan Liu, Xianglong Liu
  * Beihang University, National University of Singapore, Huazhong University of Science and Technology, Henan University of Science and Technology
  * [Arxiv2025] https://arxiv.org/abs/2504.14348
* **VEAttack: Downstream-agnostic Vision Encoder Attack against Large Vision Language Models** |  #
  * Hefei Mei, Zirui Wang, Shen You, Minjing Dong, Chang Xu
  * City University of Hong Kong, University of Sydney
  * [Arxiv2025] https://arxiv.org/abs/2505.17440
* **Attention! You Vision Language Model Could Be Maliciously Manipulated** |  #
  * Xiaosen Wang, Shaokang Wang, Zhijin Ge, Yuyang Luo, Shudong Zhang
  * Huazhong University of Science and Technology, Shanghai Jiaotong University, Xidian University, Brown University
  * [Arxiv2025] https://arxiv.org/abs/2505.19911
* **Adversarial Attacks against Closed-Source MLLMs via Feature Optimal Alignment** |  #
  * Xiaojun Jia, Sensen Gao, Simeng Qin, Tianyu Pang, Chao Du, Yihao Huang, Xinfeng Li, Yiming Li, Bo Li, Yang Liu
  * Nanyang Technological University, MBZUAI, Sea AI Lab, University of Illinois Urbana-Champaign
  * [Arxiv2025] https://arxiv.org/abs/2505.21494
* **Seeing the Threat: Vulnerabilities in Vision-Language Models to Adversarial Attack** |  #
  * Juan Ren, Mark Dras, Usman Naseem
  * Macquarie University
  * [Arxiv2025] https://arxiv.org/abs/2505.21967
* **Revisiting CroPA: A Reproducibility Study and Enhancements for Cross-Prompt Adversarial Transferability in Vision-Language Models** |  #
  * Atharv Mittal, Agam Pandey, Amritanshu Tiwari, Sukrit Jindal, Swadesh Swain
  * Mehta Family School of Data Science and Artificial Intelligence
  * [Arxiv2025] https://arxiv.org/abs/2506.22982
* **CAVALRY-V: A Large-Scale Generator Framework for Adversarial Attacks on Video MLLMs** |  #
  * Jiaming Zhang, Rui Hu, Qing Guo, Wei Yang Bryan Lim
  * Nanyang Technological University, Beijing Jiaotong University, A*STAR
  * [Arxiv2025] https://arxiv.org/abs/2507.00817
* **RECALLED: An Unbounded Resource Consumption Attack on Large Vision-Language Models** |  #
  * Haoran Gao, Yuanhe Zhang, Zhenhong Zhou, Lei Jiang, Fanyu Meng, Yujia Xiao, Kun Wang, Yang Liu, Junlan Feng
  * China Mobile Research Institute, Beijing University of Posts and Telecommunications, Nanyang Technological University, University of Science and Technology of China
  * [Arxiv2025] https://arxiv.org/abs/2507.18053
* **Imperceptible Transfer Attack on Large Vision-Language Models** |  #
  * Xiaowen Cai, Daizong Liu, Runwei Guan, Pan Zhou
  * Huazhong University of Science and Technology, Peking University, University of Liverpool
  * [ICASSP2025] https://ieeexplore.ieee.org/abstract/document/10890065/
* **X-Transfer Attacks: Towards Super Transferable Adversarial Attacks on CLIP** |  #
  * Hanxun Huang, Sarah Erfani, Yige Li, Xingjun Ma, James Bailey
  * The University of Melbourne, Singapore Management University, Fudan University
  * [ICML2025] https://arxiv.org/abs/2505.05528

## Jailbreak-Attack
* **Are aligned neural networks adversarially aligned?** | 
  * Nicholas Carlini, Milad Nasr, Christopher A. Choquette-Choo, Matthew Jagielski, Irena Gao, Anas Awadalla, Pang Wei Koh, Daphne Ippolito, Katherine Lee, Florian Tramer, Ludwig Schmidt
  * Google DeepMind, Stanford, University of Washington, ETH Zurich
  * [NeurIPs2023] https://arxiv.org/abs/2306.15447
* **FigStep: Jailbreaking Large Vision-language Models via Typographic Visual Prompts** | [Github](https://github.com/ThuCCSLab/FigStep)
  * Yichen Gong, Delong Ran, Jinyuan Liu, Conglei Wang, Tianshuo Cong, Anyu Wang, Sisi Duan, Xiaoyun Wang
  * Tsinghua University, Shandong University, Carnegie Mellon University
  * [Arxiv2023] https://arxiv.org/abs/2311.05608
* **Jailbreaking GPT-4V via Self-Adversarial Attacks with System Prompts** | 
  * Yuanwei Wu, Xiang Li, Yixin Liu, Pan Zhou, Lichao Sun
  * Huazhong University of Science and Technology, Lehigh University
  * [Arxiv2023] https://arxiv.org/abs/2311.09127
* **MM-SafetyBench: A Benchmark for Safety Evaluation of Multimodal Large Language Models** | [Github](https://github.com/isXinLiu/MM-SafetyBench)
  * Xin Liu, Yichen Zhu, Jindong Gu, Yunshi Lan, Chao Yang, Yu Qiao
  * Shanghai AI Laboratory, East China Normal University, Midea Group, University of Oxford
  * [Arxiv2023] https://arxiv.org/abs/2311.17600
* **Visual Adversarial Examples Jailbreak Aligned Large Language Models** | [Github](https://github.com/Unispac/Visual-Adversarial-Examples-Jailbreak-Large-Language-Models)
  * Xiangyu Qi, Kaixuan Huang, Ashwinee Panda, Peter Henderson, Mengdi Wang, Prateek Mittal
  * Princeton University, Stanford University
  * [AAAI2024] https://arxiv.org/abs/2306.13213
* **Jailbreak in pieces: Compositional Adversarial Attacks on Multi-Modal Language Models** | 
  * Erfan Shayegani, Yue Dong, Nael Abu-Ghazaleh
  * University of California
  * [ICLR2024] https://arxiv.org/abs/2307.14539
* **Agent Smith: A Single Image Can Jailbreak One Million Multimodal LLM Agents Exponentially Fast** | [Github](https://github.com/sail-sg/Agent-Smith)
  * Xiangming Gu, Xiaosen Zheng, Tianyu Pang, Chao Du, Qian Liu, Ye Wang, Jing Jiang, Min Lin
  * Sea AI Lab, National University of Singapore, Singapore Management University
  * [ICML2024] https://arxiv.org/abs/2402.08567
* **Learning To See But Forgetting To Follow: Visual Instruction Tuning Makes LLMs More Prone To Jailbreak Attacks** | [Github](https://github.com/gpantaz/vl_jailbreak)
  * Georgios Pantazopoulos, Amit Parekh, Malvina Nikandrou, Alessandro Suglia
  * Heriot-Watt University
  * [COLINGworkshop2024] https://arxiv.org/abs/2405.04403
* **Jailbreaking Attack against Multimodal Large Language Model** | 
  * Zhenxing Niu, Haodong Ren, Xinbo Gao, Gang Hua, Rong Jin
  * Xidian University, Wormpex AI Research, Meta
  * [Arxiv2024] https://arxiv.org/abs/2402.02309
* **ImgTrojan: Jailbreaking Vision-Language Models with ONE Image** | [Github](https://github.com/xijia-tao/ImgTrojan)
  * Xijia Tao, Shuai Zhong, Lei Li, Qi Liu, Lingpeng Kong
  * The University of Hong Kong
  * [Arxiv2024] https://arxiv.org/abs/2403.02910
* **Images are Achilles' Heel of Alignment: Exploiting Visual Vulnerabilities for Jailbreaking Multimodal Large Language Models** | [Github](https://github.com/AoiDragon/HADES)
  * Yifan Li, Hangyu Guo, Kun Zhou, Wayne Xin Zhao, Ji-Rong Wen
  * Renmin University of China, Beijing Key Laboratory of Big Data Management and Analysis Methods
  * [Arxiv2024] https://arxiv.org/abs/2403.09792
* **Red Teaming GPT-4V: Are GPT-4V Safe Against Uni/Multi-Modal Jailbreak Attacks?** | 
  * Shuo Chen, Zhen Han, Bailan He, Zifeng Ding, Wenqian Yu, Philip Torr, Volker Tresp, Jindong Gu
  * LMU Munich, University of Oxford, Siemens AG, Munich Center for Machine Learning, Wuhan University
  * [Arxiv2024] https://arxiv.org/abs/2404.03411
* **JailBreakV-28K: A Benchmark for Assessing the Robustness of MultiModal Large Language Models against Jailbreak Attacks** | [Github](https://github.com/EddyLuo1232/JailBreakV_28K)
  * Weidi Luo, Siyuan Ma, Xiaogeng Liu, Xiaoyu Guo, Chaowei Xiao
  * The Ohio State University, University of Wisconsin-Madison
  * [Arxiv2024] https://arxiv.org/abs/2404.03027
* **Unbridled Icarus: A Survey of the Potential Perils of Image Inputs in Multimodal Large Language Model Security** | 
  * Yihe Fan, Yuxin Cao, Ziyu Zhao, Ziyao Liu, Shaofeng Li
  * TongJi University, Tsinghua University, Beijing University of Technology, Nanyang Technological University,  Peng Cheng Laboratory
  * [Arxiv2024] https://arxiv.org/abs/2404.05264
* **White-box Multimodal Jailbreaks Against Large Vision-Language Models** | 
  * Ruofan Wang, Xingjun Ma, Hanxu Zhou, Chuanjun Ji, Guangnan Ye, Yu-Gang Jiang
  * Fudan University, Shanghai Jiao Tong University, DataGrand Tech
  * [Arxiv2024] https://arxiv.org/abs/2405.17894
* **From LLMs to MLLMs: Exploring the Landscape of Multimodal Jailbreaking** | 
  * Siyuan Wang, Zhuohan Long, Zhihao Fan, Zhongyu Wei
  * University of Southern California, Fudan University, Alibaba Inc.
  * [Arxiv2024] https://arxiv.org/abs/2406.14859
* **Unveiling the Safety of GPT-4o: An Empirical Study using Jailbreak Attacks** | 
  * Zonghao Ying, Aishan Liu, Xianglong Liu, Dacheng Tao
  * Beihang University, Nanyang Technological University
  * [Arxiv2024] https://arxiv.org/abs/2406.06302
* **Visual-RolePlay: Universal Jailbreak Attack on MultiModal Large Language Models via Role-playing Image Character** | 
  * Siyuan Ma, Weidi Luo, Yu Wang, Xiaogeng Liu
  * University of Wisconsin–Madison, The Ohio State University, Peking University
  * [Arxiv2024] https://arxiv.org/abs/2405.20773
* **Arondight: Red Teaming Large Vision Language Models with Auto-generated Multi-modal Jailbreak Prompts** | 
  * Yi Liu, Chengjun Cai, Xiaoli Zhang, Xingliang Yuan, Cong Wang
  * Stanford, Harvard, Anthropic, Constellation, MIT, UC Berkeley
  * [Arxiv2024] https://arxiv.org/abs/2407.15050
* **When Do Universal Image Jailbreaks Transfer Between Vision-Language Models?** | 
  * Rylan Schaeffer, Dan Valentine, Luke Bailey, James Chua, Cristóbal Eyzaguirre, Zane Durante, Joe Benton, Brando Miranda, Henry Sleight, John Hughes, Rajashree Agrawal, Mrinank Sharma, Scott Emmons, Sanmi Koyejo, Ethan Perez
  * City University of Hong Kong, University of Science and Technology, The University of Melbourne
  * [Arxiv2024] https://arxiv.org/abs/2407.15211
* **MMJ-Bench: A Comprehensive Study on Jailbreak Attacks and Defenses for Vision Language Models** | 
  * Fenghua Weng, Yue Xu, Chengyan Fu, Wenjie Wang
  * ShanghaiTech University
  * [Arxiv2024] https://arxiv.org/abs/2408.08464
* **UniGuard: Towards Universal Safety Guardrails for Jailbreak Attacks on Multimodal Large Language Models** | 
  * Sejoon Oh, Yiqiao Jin, Megha Sharma, Donghyun Kim, Eric Ma, Gaurav Verma, Srijan Kumar
  * Netflix, Georgia Institute of Technology
  * [Arxiv2024] https://arxiv.org/abs/2411.01703
* **Zer0-Jack: A Memory-efficient Gradient-based Jailbreaking Method for Black-box Multi-modal Large Language Models** | 
  * Tiejin Chen, Kaishen Wang, Hua Wei
  * Arizona State University
  * [Arxiv2024] https://arxiv.org/abs/2411.07559
* **Jailbreak Large Visual Language Models Through Multi-Modal Linkage** | [Github](https://github.com/wangyu-ovo/MML) 
  * Yu Wang, Xiaofei Zhou, Yichen Wang, Geyuan Zhang, Tianxing He
  * Chinese Academy of Sciences, University of Chinese Academy of Sciences, Tsinghua University, Shanghai Qi Zhi Institute, University of Chicago
  * [Arxiv2024] https://arxiv.org/abs/2412.00473
* **Heuristic-Induced Multimodal Risk Distribution Jailbreak Attack for Multimodal Large Language Models** |  
  * Ma Teng, Jia Xiaojun, Duan Ranjie, Li Xinfeng, Huang Yihao, Chu Zhixuan, Liu Yang, Ren Wenqi
  * Sun Yat-Sen University, Nanyang Technological University, Alibaba Group, Zhejiang University
  * [Arxiv2024] https://arxiv.org/abs/2412.05934
* **Retention Score: Quantifying Jailbreak Risks for Vision Language Models** |  
  * Zaitang Li, Pin-Yu Chen, Tsung-Yi Ho
  * The Chinese University of Hong Kong, IBM Research
  * [AAAI2025] https://arxiv.org/abs/2412.17544
* **Jailbreaking Multimodal Large Language Models via Shuffle Inconsistency** |  
  * Shiji Zhao, Ranjie Duan, Fengxiang Wang, Chi Chen, Caixin Kang, Jialing Tao, YueFeng Chen, Hui Xue, Xingxing Wei
  * Beihang University
  * [Arxiv2025] https://arxiv.org/abs/2501.04931
* **Distraction is All You Need for Multimodal Large Language Model Jailbreaking** |  #
  * Zuopeng Yang, Jiluan Fan, Anli Yan, Erdun Gao, Xin Lin, Tao Li, Kanghua mo, Changyu Dong
  * Guangzhou University, The University of Adelaide, Shanghai Jiao Tong University
  * [Arxiv2025] https://arxiv.org/abs/2502.10794
* **FC-Attack: Jailbreaking Large Vision-Language Models via Auto-Generated Flowcharts** |  #
  * Ziyi Zhang, Zhen Sun, Zongmin Zhang, Jihui Guo, Xinlei He
  * The Hong Kong University of Science and Technology, The University of Hong Kong
  * [Arxiv2025] https://arxiv.org/abs/2502.21059
* **Utilizing Jailbreak Probability to Attack and Safeguard Multimodal LLMs** |  #
  * Wenzhuo Xu, Zhipeng Wei, Xiongtao Sun, Deyue Zhang, Dongdong Yang, Quanchen Zou, Xiangzheng Zhang
  * 360 AI Security Lab, Xidian University
  * [Arxiv2025] https://arxiv.org/abs/2503.06989
* **Making Every Step Effective: Jailbreaking Large Vision-Language Models Through Hierarchical KV Equalization** |  #
  * Shuyang Hao, Yiwei Wang, Bryan Hooi, Jun Liu, Muhao Chen, Zi Huang, Yujun Cai
  * Southeast University, University of California, National University of Singapore, Lancaster University, University of Queensland
  * [Arxiv2025] https://arxiv.org/abs/2503.11750
* **Playing the Fool: Jailbreaking LLMs and Multimodal LLMs with Out-of-Distribution Strategy** |  #
  * Joonhyun Jeong, Seyun Bae, Yeonsung Jung, Jaeryong Hwang, Eunho Yang
  * NAVER Cloud, Korea Advanced Institute of Science and Technology, Republic of Korea Naval Academy, AITRICS
  * [Arxiv2025] https://arxiv.org/abs/2503.20823
* **PiCo: Jailbreaking Multimodal Large Language Models via Pictorial Code Contextualization** |  #
  * Aofan Liu, Lulu Tang, Ting Pan, Yuguo Yin, Bin Wang, Ao Yang
  * Wuhan University, Peking University, Beijing Academy of Artificial Intelligence
  * [Arxiv2025] https://arxiv.org/abs/2504.01444
* **JailDAM: Jailbreak Detection with Adaptive Memory for Vision-Language Model** |  #
  * Yi Nian, Shenzhe Zhu, Yuehan Qin, Li Li, Ziyi Wang, Chaowei Xiao, Yue Zhao
  * University of Southern California, University of Toronto, University of Maryland, University of Wisconsin-Madison
  * [Arxiv2025] https://arxiv.org/abs/2504.03770
* **BadNAVer: Exploring Jailbreak Attacks On Vision-and-Language Navigation** |  #
  * Wenqi Lyu, Zerui Li, Yanyuan Qiao, Qi Wu
  * University of Adelaide
  * [Arxiv2025] https://arxiv.org/abs/2505.12443
* **Implicit Jailbreak Attacks via Cross-Modal Information Concealment on Vision-Language Models** |  #
  * Zhaoxin Wang, Handing Wang, Cong Tian, Yaochu Jin
  * Xidian University, Westlake University
  * [Arxiv2025] https://arxiv.org/abs/2505.16446
* **VisCRA: A Visual Chain Reasoning Attack for Jailbreaking Multimodal Large Language Models** |  #
  * Bingrui Sima, Linhua Cong, Wenxuan Wang, Kun He
  * Huazhong University of Science and Technology, Hong Kong University of Science and Technology
  * [Arxiv2025] https://arxiv.org/abs/2505.19684
* **Align is not Enough: Multimodal Universal Jailbreak Attack against Multimodal Large Language Models** |  #
  * Youze Wang, Wenbo Hu, Yinpeng Dong, Jing Liu, Hanwang Zhang, Richang Hong
  * Hefei University of Technology, Tsinghua University, Chinese Academy of Science, Nanyang Technological University
  * [Arxiv2025] https://arxiv.org/abs/2506.01307
* **Cross-Modal Obfuscation for Jailbreak Attacks on Large Vision-Language Models** |  #
  * Lei Jiang, Zixun Zhang, Zizhou Wang, Xiaobing Sun, Zhen Li, Liangli Zhen, Xiaohua Xu
  * University of Science and Technology of China, The Chinese University of Hong Kong, A*STAR
  * [Arxiv2025] https://arxiv.org/abs/2506.16760
* **Visual Contextual Attack: Jailbreaking MLLMs with Image-Driven Context Injection** |  #
  * Ziqi Miao, Yi Ding, Lijun Li, Jing Shao
  * Shanghai Artificial Intelligence Laboratory, Purdue University
  * [Arxiv2025] https://arxiv.org/abs/2507.02844
* **PRISM: Programmatic Reasoning with Image Sequence Manipulation for LVLM Jailbreaking** |  #
  * Quanchen Zou, Zonghao Ying, Moyang Chen, Wenzhuo Xu, Yisong Xiao, Yakai Li, Deyue Zhang, Dongdong Yang, Zhao Liu, Xiangzheng Zhang
  * 360 AI Security Lab, Beihang University, Wenzhou-Kean University, University of the Chinese Academy of Sciences
  * [Arxiv2025] https://arxiv.org/abs/2507.21540

## Prompt-Injection
* **Abusing Images and Sounds for Indirect Instruction Injection in Multi-Modal LLMs** | 
  * Eugene Bagdasaryan, Tsung-Yin Hsieh, Ben Nassi, Vitaly Shmatikov
  * Cornell Tech
  * [Arxiv2023] https://arxiv.org/abs/2307.10490
* **Can Language Models be Instructed to Protect Personal Information?** | 
  * Yang Chen, Ethan Mendes, Sauvik Das, Wei Xu, Alan Ritter
  * Georgia Institute of Technology, Carnegie Mellon University
  * [Arxiv2023] https://arxiv.org/abs/2310.02224
* **FigStep: Jailbreaking Large Vision-language Models via Typographic Visual Prompts** | [Github](https://github.com/ThuCCSLab/FigStep)
  * Yichen Gong, Delong Ran, Jinyuan Liu, Conglei Wang, Tianshuo Cong, Anyu Wang, Sisi Duan, Xiaoyun Wang
  * Tsinghua University, Shandong University, Carnegie Mellon University
  * [Arxiv2023] https://arxiv.org/abs/2311.05608
* **MM-SafetyBench: A Benchmark for Safety Evaluation of Multimodal Large Language Models** | [Github](https://github.com/isXinLiu/MM-SafetyBench)
  * Xin Liu, Yichen Zhu, Jindong Gu, Yunshi Lan, Chao Yang, Yu Qiao
  * Shanghai AI Laboratory, East China Normal University, Midea Group, University of Oxford
  * [Arxiv2023] https://arxiv.org/abs/2311.17600
* **MLLM-Protector: Ensuring MLLM's Safety without Hurting Performance** | [Github](https://github.com/pipilurj/MLLM-protector)
  * Renjie Pi, Tianyang Han, Yueqi Xie, Rui Pan, Qing Lian, Hanze Dong, Jipeng Zhang, Tong Zhang
  * The Hong Kong University of Science and Technology, University of Illinois at Urbana-Champaign, The Hong Kong Polytechnic University
  * [Arxiv2024] https://arxiv.org/abs/2401.02906
* **Vision-LLMs Can Fool Themselves with Self-Generated Typographic Attacks** | [Github](https://github.com/mqraitem/Self-Gen-Typo-Attack)
  * Maan Qraitem, Nazia Tasnim, Piotr Teterwak, Kate Saenko, Bryan A. Plummer
  * Boston University
  * [Arxiv2024] https://arxiv.org/abs/2402.00626
* **Safeguarding Vision-Language Models Against Patched Visual Prompt Injectors** | 
  * Jiachen Sun, Changsheng Wang, Jiongxiao Wang, Yiwei Zhang, Chaowei Xiao
  * University of Michigan Ann arbor, University of Wisconsin Madison, University of Science and Technology of China
  * [Arxiv2024] https://arxiv.org/abs/2405.10529
* **Empirical Analysis of Large Vision-Language Models against Goal Hijacking via Visual Prompt Injection** | 
  * Subaru Kimura, Ryota Tanaka, Shumpei Miyawaki, Jun Suzuki, Keisuke Sakaguchi
  * Tohoku University, NTT Corporation
  * [Arxiv2024] https://arxiv.org/abs/2408.03554
* **Manipulation Facing Threats: Evaluating Physical Vulnerabilities in End-to-End Vision Language Action Models** | 
  * Hao Cheng, Erjia Xiao, Chengyuan Yu, Zhao Yao, Jiahang Cao, Qiang Zhang, Jiaxu Wang, Mengshu Sun, Kaidi Xu, Jindong Gu, Renjing Xu
  * The Hong Kong University of Science and Technology, University of Oxford, Hohai University, Hunan University, Drexel University, Beijing University of Technology
  * [Arxiv2024] https://arxiv.org/abs/2409.13174
* **Exploring the Transferability of Visual Prompting for Multimodal Large Language Models** | [Github](https://github.com/zycheiheihei/Transferable-Visual-Prompting) 
  * Yichi Zhang, Yinpeng Dong, Siyuan Zhan, Tianzan Min, Hang Su, Jun Zhu
  * Tsinghua University, RealAI, Pazhou Laboratory (Huangpu)
  * [CVPR2024] https://openaccess.thecvf.com/content/CVPR2024/papers/Zhang_Exploring_the_Transferability_of_Visual_Prompting_for_Multimodal_Large_Language_CVPR_2024_paper.pdf
* **Pandora's Box: Towards Building Universal Attackers against Real-World Large Vision-Language Models** | 
  * Daizong Liu, Mingyu Yang, Xiaoye Qu, Pan Zhou, Xiang Fang, Keke Tang, Yao Wan, Lichao Sun
  * Peking University, Huazhong University of Science and Technology, Nanyang Technological University, Guangzhou University, Lehigh University
  * [NeurIPS2024] https://openreview.net/forum?id=gDpWYpocE1
* **Effective Black-Box Multi-Faceted Attacks Breach Vision Large Language Model Guardrails** | 
  * Yijun Yang, Lichao Wang, Xiao Yang, Lanqing Hong, Jun Zhu
  * Tsinghua University, Huawei Noah’s Ark Lab
  * [Arxiv2025] https://arxiv.org/abs/2502.05772
* **Manipulating Multimodal Agents via Cross-Modal Prompt Injection** |  #
  * Le Wang, Zonghao Ying, Tianyuan Zhang, Siyuan Liang, Shengshan Hu, Mingchuan Zhang, Aishan Liu, Xianglong Liu
  * Beihang University, National University of Singapore, Huazhong University of Science and Technology, Henan University of Science and Technology
  * [Arxiv2025] https://arxiv.org/abs/2504.14348
* **EnvInjection: Environmental Prompt Injection Attack to Multi-modal Web Agents** |  #
  * Xilong Wang, John Bloch, Zedian Shao, Yuepeng Hu, Shuyan Zhou, Neil Zhenqiang Gong
  * Duke University
  * [Arxiv2025] https://arxiv.org/abs/2505.11717
* **Invisible Injections: Exploiting Vision-Language Models Through Steganographic Prompt Embedding** |  #
  * Chetan Pathade
  * CMU
  * [Arxiv2025] https://arxiv.org/abs/2507.22304

## Data-Poisoning
* **Shadowcast: Stealthy Data Poisoning Attacks Against Vision-Language Models** | [Github](https://github.com/umd-huang-lab/VLM-Poisoning)
  * Yuancheng Xu, Jiarui Yao, Manli Shu, Yanchao Sun, Zichu Wu, Ning Yu, Tom Goldstein, Furong Huang
  * University of Maryland, College Park, JPMorgan AI Research, University of Waterloo, Salesforce Research
  * [Arxiv2024] https://arxiv.org/abs/2402.06659
* **PoisonedRAG: Knowledge Poisoning Attacks to Retrieval-Augmented Generation of Large Language Models** | [Github](https://github.com/sleeepeer/PoisonedRAG)
  * Wei Zou, Runpeng Geng, Binghui Wang, Jinyuan Jia
  * Pennsylvania State University, Wuhan University, Illinois Institute of Technology
  * [Arxiv2024] https://arxiv.org/abs/2402.07867
* **Test-Time Backdoor Attacks on Multimodal Large Language Models** | [Github](https://github.com/sail-sg/AnyDoor)
  * Dong Lu, Tianyu Pang, Chao Du, Qian Liu, Xianjun Yang, Min Lin
  * Southern University of Science and Technology, Sea AI Lab, University of California
  * [Arxiv2024] https://arxiv.org/abs/2402.08577
* **VL-Trojan: Multimodal Instruction Backdoor Attacks against Autoregressive Visual Language Models** | 
  * Jiawei Liang, Siyuan Liang, Man Luo, Aishan Liu, Dongchen Han, Ee-Chien Chang, Xiaochun Cao
  * Sun Yat-sen University
  * [Arxiv2024] https://arxiv.org/abs/2402.13851
* **Physical Backdoor Attack can Jeopardize Driving with Vision-Large-Language Models** | 
  * Zhenyang Ni, Rui Ye, Yuxi Wei, Zhen Xiang, Yanfeng Wang, Siheng Chen
  * Shanghai Jiao Tong University, University of Illinois Urbana-Champaign, Shanghai AI Laboratory, Multi-Agent Governance & Intelligence Crew
  * [Arxiv2024] https://arxiv.org/abs/2404.12916
* **Revisiting Backdoor Attacks against Large Vision-Language Models** | 
  * Siyuan Liang, Jiawei Liang, Tianyu Pang, Chao Du, Aishan Liu, Ee-Chien Chang, Xiaochun Cao
  * National University of Singapore, Sun Yat-sen University, Beihang University
  * [Arxiv2024] https://arxiv.org/abs/2406.18844
* **TrojVLM: Backdoor Attack Against Vision Language Models** |  #
  * Weimin Lyu, Lu Pang, Tengfei Ma, Haibin Ling, Chao Chen
  * Stony Brook University
  * [ECCV2024] https://link.springer.com/chapter/10.1007/978-3-031-73650-6_27
* **Membership Inference Attacks against Large Vision-Language Models** | [Github](https://github.com/LIONS-EPFL/VL-MIA) 
  * Zhan Li, Yongtao Wu, Yihang Chen, Francesco Tonin, Elias Abad Rocamora, Volkan Cevher
  * University of California
  * [NeurIPS2024] https://arxiv.org/abs/2411.02902
* **Membership Inference Attacks Against Vision-Language Models** | [Github](https://github.com/YukeHu/vlm_mia) 
  * Yuke Hu, Zheng Li, Zhihao Liu, Yang Zhang, Zhan Qin, Kui Ren, Chun Chen
  * Zhejiang University, Shandong University, CISPA Helmholtz Center for Information Security
  * [USENIX'25] https://arxiv.org/abs/2501.18624
* **Backdooring Vision-Language Models with Out-Of-Distribution Data** |  #
  * Weimin Lyu, Jiachen Yao, Saumya Gupta, Lu Pang, Tao Sun, Lingjie Yi, Lijie Hu, Haibin Ling, Chao Chen
  * Stony Brook University, King Abdullah University of Science and Technology
  * [ICLR2025] https://openreview.net/forum?id=tZozeR3VV7
* **Stealthy Backdoor Attack in Self-Supervised Learning Vision Encoders for Large Vision Language Models** |  #
  * Zhaoyi Liu, Huan Zhang
  * University of Illinois Urbana-Champaign
  * [Arxiv2025] https://arxiv.org/abs/2502.18290
* **Spa-VLM: Stealthy Poisoning Attacks on RAG-based VLM** |  #
  * Lei Yu, Yechao Zhang, Ziqi Zhou, Yang Wu, Wei Wan, Minghui Li, Shengshan Hu, Pei Xiaobing, Jing Wang
  * Huazhong University of Science and Technology
  * [Arxiv2025] https://arxiv.org/abs/2505.23828
* **Backdoor Attack on Vision Language Models with Stealthy Semantic Manipulation** |  #
  * Zhiyuan Zhong, Zhen Sun, Yepang Liu, Xinlei He, Guanhong Tao
  * University of Utah, Hong Kong University of Science and Technology (Guangzhou), Southern University of Science and Technology
  * [Arxiv2025] https://arxiv.org/abs/2506.07214

## Special-Attacks-For-LVLM-Applications
* **Physical Backdoor Attack can Jeopardize Driving with Vision-Large-Language Models** | 
  * Zhenyang Ni, Rui Ye, Yuxi Wei, Zhen Xiang, Yanfeng Wang, Siheng Chen
  * Shanghai Jiao Tong University, University of Illinois Urbana-Champaign, Shanghai AI Laboratory, Multi-Agent Governance & Intelligence Crew
  * [Arxiv2024] https://arxiv.org/abs/2404.12916
* **Towards Transferable Attacks Against Vision-LLMs in Autonomous Driving with Typography** | 
  * Nhat Chung, Sensen Gao, Tuan-Anh Vu, Jie Zhang, Aishan Liu, Yun Lin, Jin Song Dong, Qing Guo
  * A*STAR, VNU-HCM, Nankai University, HKUST, Nanyang Technological University, Beihang University, Shanghai Jiao Tong University, National University of Singapore
  * [Arxiv2024] https://arxiv.org/abs/2405.14169
* **PG-Attack: A Precision-Guided Adversarial Attack Framework Against Vision Foundation Models for Autonomous Driving** | 
  * Jiyuan Fu, Zhaoyu Chen, Kaixun Jiang, Haijing Guo, Shuyong Gao, Wenqiang Zhang
  * Fudan University
  * [Arxiv2024] https://arxiv.org/abs/2407.13111
* **Visual Adversarial Attack on Vision-Language Models for Autonomous Driving** | 
  * Tianyuan Zhang, Lu Wang, Xinwei Zhang, Yitong Zhang, Boyi Jia, Siyuan Liang, Shengshan Hu, Qiang Fu, Aishan Liu, Xianglong Liu
  * Beihang University, National University of Singapore, Huazhong University of Science and Technology
  * [Arxiv2024] https://arxiv.org/abs/2411.18275
* **AutoTrust: Benchmarking Trustworthiness in Large Vision Language Models for Autonomous Driving** | [Github](https://github.com/taco-group/AutoTrust) 
  * Shuo Xing, Hongyuan Hua, Xiangbo Gao, Shenzhe Zhu, Renjie Li, Kexin Tian, Xiaopeng Li, Heng Huang, Tianbao Yang, Zhangyang Wang, Yang Zhou, Huaxiu Yao, Zhengzhong Tu
  * Texas A&M University, University of Toronto, University of Michigan, University of Wisconsin-Madison, University of Maryland, University of Texas at Austin, University of North Carolina at Chapel Hill
  * [Arxiv2024] https://arxiv.org/abs/2412.15206
* **Black-Box Adversarial Attack on Vision Language Models for Autonomous Driving** | 
  * Lu Wang, Tianyuan Zhang, Yang Qu, Siyuan Liang, Yuwei Chen, Aishan Liu, Xianglong Liu, Dacheng Tao
  * Beihang University, National University of Singapore, Aviation Industry Development Research Center of China, Nanyang Technological University
  * [Arxiv2025] https://arxiv.org/abs/2501.13563
* **On the Safety Concerns of Deploying LLMs/VLMs in Robotics: Highlighting the Risks and Vulnerabilities** | 
  * Xiyang Wu, Ruiqi Xian, Tianrui Guan, Jing Liang, Souradip Chakraborty, Fuxiao Liu, Brian M. Sadler, Dinesh Manocha, Amrit Bedi
  * University of Maryland
  * [VLADR2024] https://openreview.net/forum?id=4FpuOMoxsX
* **Exploring the Robustness of Decision-Level Through Adversarial Attacks on LLM-Based Embodied Models** | 
  * Shuyuan Liu, Jiawei Chen, Shouwei Ruan, Hang Su, Zhaoxia Yin
  * East China Normal University, Beihang University, Tsinghua University
  * [ACMMM2024] https://arxiv.org/abs/2405.19802
* **Towards Physically-Realizable Adversarial Attacks in Embodied Vision Navigation** | 
  * Meng Chen, Jiawei Tu, Chao Qi, Yonghao Dang, Feng Zhou, Wei Wei, Jianqin Yin
  * Beijing University of Posts and Telecommunications, China Academy of Railway Sciences Corporation Limited
  * [Arxiv2024] https://arxiv.org/abs/2409.10071
* **Manipulation Facing Threats: Evaluating Physical Vulnerabilities in End-to-End Vision Language Action Models** | 
  * Hao Cheng, Erjia Xiao, Chengyuan Yu, Zhao Yao, Jiahang Cao, Qiang Zhang, Jiaxu Wang, Mengshu Sun, Kaidi Xu, Jindong Gu, Renjing Xu
  * The Hong Kong University of Science and Technology, University of Oxford, Hohai University, Hunan University, Drexel University, Beijing University of Technology
  * [Arxiv2024] https://arxiv.org/abs/2409.13174
* **TrojanRobot: Physical-World Backdoor Attacks Against VLM-based Robotic Manipulation** | [Github](https://trojanrobot.github.io/index.html#physical) 
  * Xianlong Wang, Hewen Pan, Hangtao Zhang, Minghui Li, Shengshan Hu, Ziqi Zhou, Lulu Xue, Peijin Guo, Yichen Wang, Wei Wan, Aishan Liu, Leo Yu Zhang
  * Huazhong University of Science and Technology, Beihang University, Griffith University
  * [Arxiv2024] https://arxiv.org/abs/2411.11683
* **Exploring the Adversarial Vulnerabilities of Vision-Language-Action Models in Robotics** | 
  * Taowen Wang, Dongfang Liu, James Chenhao Liang, Wenhao Yang, Qifan Wang, Cheng Han, Jiebo Luo, Ruixiang Tang
  * Rochester Institute of Technology, U.S. Naval Research Laboratory, Lamar University, Meta AI, University of Missouri - Kansas City, University of Rochester, Rutgers University
  * [Arxiv2024] https://arxiv.org/abs/2411.13587
* **BadRobot: Jailbreaking Embodied LLMs in the Physical World** | [Github](https://embodied-llms-safety.github.io/) 
  * Hangtao Zhang, Chenyu Zhu, Xianlong Wang, Ziqi Zhou, Changgan Yin, Minghui Li, Lulu Xue, Yichen Wang, Shengshan Hu, Aishan Liu, Peijin Guo, Leo Yu Zhang
  * Huazhong University of Science and Technology, Griffith University, Beihang University
  * [ICLR2025] https://arxiv.org/abs/2407.20242
* **Medical MLLM is Vulnerable: Cross-Modality Jailbreak and Mismatched Attacks on Medical Multimodal Large Language Models** | [Github](https://github.com/dirtycomputer/O2M_attack)
  * Xijie Huang, Xinyuan Wang, Hantao Zhang, Yinghao Zhu, Jiawen Xi, Jingkun An, Hao Wang, Hao Liang, Chengwei Pan
  * Beihang University, University of Science and Technology of China, Peking University
  * [Arxiv2024] https://arxiv.org/abs/2405.20775
* **CARES: A Comprehensive Benchmark of Trustworthiness in Medical Vision Language Models** | [Github](https://cares-ai.github.io/)
  * Peng Xia, Ze Chen, Juanxi Tian, Yangrui Gong, Ruibo Hou, Yue Xu, Zhenbang Wu, Zhiyuan Fan, Yiyang Zhou, Kangyu Zhu, Wenhao Zheng, Zhaoyang Wang, Xiao Wang, Xuchao Zhang, Chetan Bansal, Marc Niethammer, Junzhou Huang, Hongtu Zhu, Yun Li, Jimeng Sun, Zongyuan Ge, Gang Li, James Zou, Huaxiu Yao
  * UNC-Chapel Hill, Monash University, Brown University, University of Washington, Microsoft Research, UT Arlington, UIUC, Stanford University, HKUST
  * [NeurIPS2024] https://arxiv.org/abs/2406.06007
* **Medical Multimodal Model Stealing Attacks via Adversarial Domain Alignment** | 
  * Yaling Shen, Zhixiong Zhuang, Kun Yuan, Maria-Irina Nicolae, Nassir Navab, Nicolas Padoy, Mario Fritz
  * Bosch Center for Artificial Intelligence, Technical University of Munich, Munich Center for Machine Learning, Saarland University, University of Strasbourg, IHU Strasbourg, CISPA Helmholtz Center for Information Security
  * [Arxiv2025] https://arxiv.org/abs/2502.02438
* **Are VLMs Ready for Autonomous Driving? An Empirical Study from the Reliability, Data, and Metric Perspectives** | [Github](https://github.com/drive-bench/toolkit)   #
  * Shaoyuan Xie, Lingdong Kong, Yuhao Dong, Chonghao Sima, Wenwei Zhang, Qi Alfred Chen, Ziwei Liu, Liang Pan
  * University of California, Shanghai AI Laboratory, National University of Singapore, Nanyang Technological University, The University of Hong Kong
  * [ICCV2025] https://arxiv.org/abs/2501.04003

## Benchmarks
* **Are Vision-Language Models Safe in the Wild? A Meme-Based Benchmark Study** |   #
  * DongGeon Lee, Joonwon Jang, Jihae Jeong, Hwanjo Yu
  * POSTECH, LG AI Research
  * [Arxiv2025] https://arxiv.org/abs/2505.15389
