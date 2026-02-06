<h1 align="center">🤗🤗🤗 Awesome-LVLM/MLLM-Safety 🤗🤗🤗</h1>

<p align="center"><em>Curated list of Large Vision-Language Model (LVLM) Safety resources, aligned with our work:</em><br><strong>A Survey of Safety on Large Vision-Language Models: Attacks, Defenses and Evaluations</strong></p>

<p align="center">
    <a href="https://arxiv.org/abs/2502.14881"><img src="https://img.shields.io/badge/arXiv-2502.14881-b31b1b.svg" alt="arXiv Badge"></a>
    <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome Badge"></a>
    <img src="https://visitor-badge.laobi.icu/badge?page_id=xuankunrong.awesome-lvlm-safety" alt="visitors"/>
    <a href="https://creativecommons.org/licenses/by-nc/4.0/"><img src="https://img.shields.io/badge/License-CC_BY--NC_4.0-lightgrey.svg" alt="License Badge"></a>
    <a href="https://github.com/XuankunRong/Awesome-LVLM-Safety"><img src="https://img.shields.io/github/stars/XuankunRong/Awesome-LVLM-Safety?style=social" alt="GitHub stars"></a>
</p>

<h2> 🙌 Abstract </h2>

With the rapid advancement of Large Vision-Language Models (LVLMs), also referred to as Multimodal Large Language Models (MLLMs), ensuring their safety has emerged as a crucial area of research. This survey provides a comprehensive analysis of LVLM safety, covering key aspects such as attacks, defenses, and evaluation methods. We introduce a unified framework that integrates these interrelated components, offering a holistic perspective on the vulnerabilities of LVLMs and the corresponding mitigation strategies. Through an analysis of the LVLM lifecycle, we introduce a classification framework that distinguishes between inference and training phases, with further subcategories to provide deeper insights. Furthermore, we highlight limitations in existing research and outline future directions aimed at strengthening the robustness of LVLMs. As part of our research, we conduct a set of safety evaluations on the latest LVLM, Deepseek Janus-Pro, and provide a theoretical analysis of the results. Our findings provide strategic recommendations for advancing LVLM safety and ensuring their secure and reliable deployment in high-stakes, real-world applications. This survey aims to serve as a cornerstone for future research, facilitating the development of models that not only push the boundaries of multimodal intelligence but also adhere to the highest standards of security and ethical integrity.

<h2> 📜 Table of Contents </h2>

- [Awesome Papers](#awesome-papers)
  - [Attacks](#attacks)
  - [Defenses](#defenses)
  - [Evaluations](#evaluations)
- [Evaluation on Janus-Pro](#januspro)
- [Contact](#contact)
- [Citation](#citation)

<h2 id="awesome-papers"> 👑 Awesome Papers </h2>

<h3 id="attacks"> <img src="assets/attack.png" alt="Icon" width="20" style="vertical-align:middle"/> Attacks </h3>

* **[2023.05.26]** **[On Evaluating Adversarial Robustness of Large Vision-Language Models](https://arxiv.org/abs/2305.16934)** [![GitHub stars](https://img.shields.io/github/stars/yunqing-me/AttackVLM?style=social)](https://github.com/yunqing-me/AttackVLM)
  * Yunqing Zhao, Tianyu Pang, Chao Du, Xiao Yang, Chongxuan Li, Ngai-Man Cheung, Min Lin
  * Singapore University of Technology and Design, Sea AI Lab, Tsinghua University, Renmin University of China
  * [NeurIPS'23]
* **[2023.06.22] [Visual Adversarial Examples Jailbreak Aligned Large Language Models](https://arxiv.org/abs/2306.13213)** [![GitHub stars](https://img.shields.io/github/stars/unispac/visual-adversarial-examples-jailbreak-large-language-models?style=social)](https://github.com/unispac/visual-adversarial-examples-jailbreak-large-language-models)
  * Xiangyu Qi, Kaixuan Huang, Ashwinee Panda, Peter Henderson, Mengdi Wang, Prateek Mittal
  * Princeton University, Stanford University
  * [AAAI'24 Oral]
* **[2023.07.19]** **[Abusing Images and Sounds for Indirect Instruction Injection in Multi-Modal LLMs](https://arxiv.org/abs/2307.10490)** [![GitHub stars](https://img.shields.io/github/stars/ebagdasa/multimodal_injection?style=social)](https://github.com/ebagdasa/multimodal_injection)
  * Eugene Bagdasaryan, Tsung-Yin Hsieh, Ben Nassi, Vitaly Shmatikov
  * Cornell Tech
  * [arXiv'23]
* **[2023.07.26]** **[Jailbreak in pieces: Compositional Adversarial Attacks on Multi-Modal Language Models](https://arxiv.org/abs/2307.14539)** [![GitHub stars](https://img.shields.io/github/stars/erfanshayegani/Jailbreak-In-Pieces?style=social)](https://github.com/erfanshayegani/Jailbreak-In-Pieces)
  * Erfan Shayegani, Yue Dong, Nael Abu-Ghazaleh
  * University of California, Riverside
  * [ICLR'24]
* **[2023.08.23]** **[On the Adversarial Robustness of Multi-Modal Foundation Models](https://arxiv.org/abs/2308.10741)** [![GitHub stars](https://img.shields.io/github/stars/chs20/robustvlm?style=social)](https://github.com/chs20/robustvlm)
  * Christian Schlarmann, Matthias Hein
  * University of Tübingen
  * [ICCV'23 AROW]
* **[2023.09.01]** **[Image Hijacks: Adversarial Images can Control Generative Models at Runtime](https://arxiv.org/abs/2309.00236)** [![GitHub stars](https://img.shields.io/github/stars/euanong/image-hijacks?style=social)](https://github.com/euanong/image-hijacks)
  * Luke Bailey, Euan Ong, Stuart Russell, Scott Emmons
  * Harvard University, Cambridge University , University of California, Berkeley
  * [ICML'24]
* **[2023.09.20]** **[How Robust is Google&#39;s Bard to Adversarial Image Attacks?](https://arxiv.org/abs/2309.11751)** [![GitHub stars](https://img.shields.io/github/stars/thu-ml/attack-bard?style=social)](https://github.com/thu-ml/attack-bard)
  * Yinpeng Dong, Huanran Chen, Jiawei Chen, Zhengwei Fang, Xiao Yang, Yichi Zhang, Yu Tian, Hang Su, Jun Zhu
  * Tsinghua University, RealAI
  * [NeurIPS'23 Workshop]
* **[2023.11.09]** **[FigStep: Jailbreaking Large Vision-language Models via Typographic Visual Prompts](https://arxiv.org/abs/2311.05608)** [![GitHub stars](https://img.shields.io/github/stars/thuccslab/figstep?style=social)](https://github.com/thuccslab/figstep)
  * Yichen Gong, Delong Ran, Jinyuan Liu, Conglei Wang, Tianshuo Cong, Anyu Wang, Sisi Duan, Xiaoyun Wang
  * Tsinghua University, Carnegie Mellon University, Zhongguancun Laboratory, National Financial Cryptography Research Center, Shandong Institute of Blockchain, Shandong University
  * [AAAI'25]
* **[2023.12.04]** **[InstructTA: Instruction-Tuned Targeted Attack for Large Vision-Language Models](https://arxiv.org/abs/2312.01886)** [![GitHub stars](https://img.shields.io/github/stars/xunguangwang/instructta?style=social)](https://github.com/xunguangwang/instructta)
  * Xunguang Wang, Zhenlan Ji, Pingchuan Ma, Zongjie Li, Shuai Wang
  * The Hong Kong University of Science and Technology
  * [arXiv'23]
* **[2024.01.20]** **[Inducing High Energy-Latency of Large Vision-Language Models with Verbose Images](https://arxiv.org/abs/2401.11170)** [![GitHub stars](https://img.shields.io/github/stars/kuofenggao/verbose_images?style=social)](https://github.com/kuofenggao/verbose_images)
  * Kuofeng Gao, Yang Bai, Jindong Gu, Shu-Tao Xia, Philip Torr, Zhifeng Li, Wei Liu
  * Tsinghua University, Tencent Technology (Beijing) Co.Ltd, University of Oxford, Tencent Data Platform,  Peng Cheng Laboratory
  * [ICLR'24]
* **[2024.02.01]** **[Vision-LLMs Can Fool Themselves with Self-Generated Typographic Attacks](https://arxiv.org/abs/2402.00626)** [![GitHub stars](https://img.shields.io/github/stars/mqraitem/self-gen-typo-attack?style=social)](https://github.com/mqraitem/self-gen-typo-attack)
  * Maan Qraitem, Nazia Tasnim, Piotr Teterwak, Kate Saenko, Bryan A. Plummer
  * Boston University
  * [NeurIPS'24]
* **[2024.02.03]** **[Jailbreaking Attack against Multimodal Large Language Model](https://arxiv.org/abs/2402.02309)** [![GitHub stars](https://img.shields.io/github/stars/abc03570128/jailbreaking-attack-against-multimodal-large-language-model?style=social)](https://github.com/abc03570128/jailbreaking-attack-against-multimodal-large-language-model)
  * Zhenxing Niu, Haodong Ren, Xinbo Gao, Gang Hua, Rong Jin
  * Xidian University, Wormpex AI Research, Meta
  * [arXiv'24]
* **[2024.02.05]** **[Shadowcast: Stealthy Data Poisoning Attacks Against Vision-Language Models](https://arxiv.org/abs/2402.06659)** [![GitHub stars](https://img.shields.io/github/stars/umd-huang-lab/vlm-poisoning?style=social)](https://github.com/umd-huang-lab/vlm-poisoning)
  * Yuancheng Xu, Jiarui Yao, Manli Shu, Yanchao Sun, Zichu Wu, Ning Yu, Tom Goldstein, Furong Huang
  * University of Maryland, University of Illinois Urbana-Champaign, Salesforce Research, Apple, University of Waterloo,  Netflix Eyeline Studios
  * [NeurIPS'24]
* **[2024.02.13]** **[Agent Smith: A Single Image Can Jailbreak One Million Multimodal LLM Agents Exponentially Fast](https://arxiv.org/abs/2402.08567)** [![GitHub stars](https://img.shields.io/github/stars/sail-sg/agent-smith?style=social)](https://github.com/sail-sg/agent-smith)
  * Xiangming Gu, Xiaosen Zheng, Tianyu Pang, Chao Du, Qian Liu, Ye Wang, Jing Jiang, Min Lin
  * Sea AI Lab, National University of Singapore, Singapore Management University
  * [ICML'24]
* **[2024.02.13]** **[Test-Time Backdoor Attacks on Multimodal Large Language Models](https://arxiv.org/abs/2402.08577)** [![GitHub stars](https://img.shields.io/github/stars/sail-sg/anydoor?style=social)](https://github.com/sail-sg/anydoor)
  * Dong Lu, Tianyu Pang, Chao Du, Qian Liu, Xianjun Yang, Min Lin
  * Southern University of Science and Technology, Sea AI Lab, University of California
  * [arXiv'24]
* **[2024.02.20]** **[The Wolf Within: Covert Injection of Malice into MLLM Societies via An MLLM Operative](https://arxiv.org/abs/2402.14859)** [![GitHub stars](https://img.shields.io/github/stars/chengshuaizhao0/the-wolf-within?style=social)](https://github.com/chengshuaizhao0/the-wolf-within)
  * Zhen Tan, Chengshuai Zhao, Raha Moraffah, Yifan Li, Yu Kong, Tianlong Chen, Huan Liu
  * Arizona State University, Michigan State University, University of North Carolina at Chapel Hill, MIT, Harvard University
  * [arXiv'24]
* **[2024.02.21]** **[VL-Trojan: Multimodal Instruction Backdoor Attacks against Autoregressive Visual Language Models](https://arxiv.org/abs/2402.13851)**
  * Jiawei Liang, Siyuan Liang, Man Luo, Aishan Liu, Dongchen Han, Ee-Chien Chang, Xiaochun Cao
  * [arXiv'24]
* **[2024.02.22]** **[Stop Reasoning! When Multimodal LLM with Chain-of-Thought Reasoning Meets Adversarial Image](https://arxiv.org/abs/2402.14899)** [![GitHub stars](https://img.shields.io/github/stars/aipenguin/stopreasoning?style=social)](https://github.com/aipenguin/stopreasoning)
  * Zefeng Wang, Zhen Han, Shuo Chen, Fan Xue, Zifeng Ding, Xun Xiao, Volker Tresp, Philip Torr, Jindong Gu
  * Technical University of Munich, LMU Munich, Huawei Technologies, University of Oxford
  * [COLM'24]
* **[2024.03.05]** **[ImgTrojan: Jailbreaking Vision-Language Models with ONE Image](https://arxiv.org/abs/2403.02910)** [![GitHub stars](https://img.shields.io/github/stars/xijia-tao/imgtrojan?style=social)](https://github.com/xijia-tao/imgtrojan)
  * Xijia Tao, Shuai Zhong, Lei Li, Qi Liu, Lingpeng Kong
  * The University of Hong Kong
  * [arXiv'24]
* **[2024.03.14]** **[Images are Achilles&#39; Heel of Alignment: Exploiting Visual Vulnerabilities for Jailbreaking Multimodal Large Language Models](https://arxiv.org/abs/2403.09792)** [![GitHub stars](https://img.shields.io/github/stars/rucaibox/hades?style=social)](https://github.com/rucaibox/hades)
  * Yifan Li, Hangyu Guo, Kun Zhou, Wayne Xin Zhao, Ji-Rong Wen
  * Renmin University of China, Beijing Key Laboratory of Big Data Management and Analysis Methods
  * [ECCV'24]
* **[2024.03.14]** **[An Image Is Worth 1000 Lies: Adversarial Transferability across Prompts on Vision-Language Models](https://arxiv.org/abs/2403.09766)** [![GitHub stars](https://img.shields.io/github/stars/haochen-luo/cropa?style=social)](https://github.com/haochen-luo/cropa)
  * Haochen Luo, Jindong Gu, Fengyuan Liu, Philip Torr
  * University of Oxford
  * [ICLR'24]
* **[2024.04.19]** **[Physical Backdoor Attack can Jeopardize Driving with Vision-Large-Language Models](https://arxiv.org/abs/2404.12916)** [![GitHub stars](https://img.shields.io/github/stars/vincentni0107/badvlmdriver?style=social)](https://github.com/vincentni0107/badvlmdriver)
  * Zhenyang Ni, Rui Ye, Yuxi Wei, Zhen Xiang, Yanfeng Wang, Siheng Chen
  * Shanghai Jiao Tong University, University of Illinois Urbana-Champaign, Shanghai AI Laboratory, Multi-Agent Governance & Intelligence Crew (MAGIC)
  * [ICML'24 Workshop]
* **[2024.05.16]** **[Adversarial Robustness for Visual Grounding of Multimodal Large Language Models](https://arxiv.org/abs/2405.09981)** [![GitHub stars](https://img.shields.io/github/stars/KuofengGao/MLLM-Grounding-Robustness?style=social)](https://github.com/KuofengGao/MLLM-Grounding-Robustness)
  * Kuofeng Gao, Yang Bai, Jiawang Bai, Yong Yang, Shu-Tao Xia
  * Tsinghua University, Tencent Security Platform, Peng Cheng Laboratory
  * [ICLR'24 Workshop]
* **[2024.05.25]** **[Visual-RolePlay: Universal Jailbreak Attack on MultiModal Large Language Models via Role-playing Image](https://arxiv.org/abs/2405.20773)**
  * Siyuan Ma, Weidi Luo, Yu Wang, Xiaogeng Liu
  * University of Wisconsin–Madison, The Ohio State University, Peking University
  * [arXiv'24]
* **[2024.05.28]** **[White-box Multimodal Jailbreaks Against Large Vision-Language Models](https://arxiv.org/abs/2405.17894)** [![GitHub stars](https://img.shields.io/github/stars/roywang021/UMK?style=social)](https://github.com/roywang021/UMK)
  * Ruofan Wang, Xingjun Ma, Hanxu Zhou, Chuanjun Ji, Guangnan Ye, Yu-Gang Jiang
  * Fudan University, Shanghai Jiaotong University
  * [MM'24]
* **[2024.06.06]** **[Jailbreak Vision Language Models via Bi-Modal Adversarial Prompt](https://arxiv.org/abs/2406.04031)** [![GitHub stars](https://img.shields.io/github/stars/NY1024/BAP-Jailbreak-Vision-Language-Models-via-Bi-Modal-Adversarial-Prompt?style=social)](https://github.com/NY1024/BAP-Jailbreak-Vision-Language-Models-via-Bi-Modal-Adversarial-Prompt)
  * Zonghao Ying, Aishan Liu, Tianyuan Zhang, Zhengmin Yu, Siyuan Liang, Xianglong Liu, Dacheng Tao
  * Beihang University, Fudan University, National University of Singapore, Nanyang Technological University
  * [arXiv'24]
* **[2024.06.19]** **[Enhancing Cross-Prompt Transferability in Vision-Language Models through Contextual Injection of Target Tokens](https://arxiv.org/abs/2406.13294)** [![GitHub stars](https://img.shields.io/github/stars/YancyKahn/CIA?style=social)](https://github.com/YancyKahn/CIA)
  * Xikang Yang, Xuehai Tang, Fuqing Zhu, Jizhong Han, Songlin Hu
  * University of Chinese Academy of Sciences
  * [arXiv'24]
* **[2024.06.27]** **[Revisiting Backdoor Attacks against Large Vision-Language Models](https://arxiv.org/abs/2406.18844)**
  * Siyuan Liang, Jiawei Liang, Tianyu Pang, Chao Du, Aishan Liu, Mingli Zhu, Xiaochun Cao, Dacheng Tao
  * National University of Singapore, Shenzhen Campus of Sun Yat-sen University, Sea AI lab, Independent Researchers, The Chinese University of Hong Kong, Shenzhen, Nanyang Technological University
  * [CVPR'25]
* **[2024.07.01]** **[Image-to-Text Logic Jailbreak: Your Imagination can Help You Do Anything](https://arxiv.org/abs/2407.02534)**
  * Xiaotian Zou, Ke Li, Yongkang Chen
  * University of Exeter, Nanjing University of Aeronautics and Astronautics
  * [arXiv'24]
* **[2024.09.28]** **[TrojVLM: Backdoor Attack Against Vision Language Models](https://arxiv.org/abs/2409.19232)**
  * Weimin Lyu, Lu Pang, Tengfei Ma, Haibin Ling, Chao Chen
  * Stony Brook University
  * [ECCV'24]
* **[2024.10.02]** **[Backdooring Vision-Language Models with Out-Of-Distribution Data](https://arxiv.org/abs/2410.01264)**
  * Weimin Lyu, Jiachen Yao, Saumya Gupta, Lu Pang, Tao Sun, Lingjie Yi, Lijie Hu, Haibin Ling, Chao Chen
  * Stony Brook University, King Abdullah University of Science and Technology
  * [ICLR'25]
* **[2024.10.09]** **[Break the Visual Perception: Adversarial Attacks Targeting Encoded Visual Tokens of Large Vision-Language Models](https://arxiv.org/abs/2410.06699)**
  * Yubo Wang, Chaohu Liu, Yanqiu Qu, Haoyu Cao, Deqiang Jiang, Linli Xu
  * University of Science and Technology of China, Tencent YouTu Lab
  * [MM'24]
* **[2024.10.29]** **[IDEATOR: Jailbreaking Large Vision-Language Models Using Themselves](https://arxiv.org/abs/2411.00827v6)** [![GitHub stars](https://img.shields.io/github/stars/roywang021/IDEATOR?style=social)](https://github.com/roywang021/IDEATOR)
  * Ruofan Wang, Juncheng Li, Yixu Wang, Bo Wang, Xiaosen Wang, Yan Teng, Yingchun Wang, Xingjun Ma, Yu-Gang Jiang
  * Fudan University, Huawei Technologies Ltd., Shanghai AI Lab
  * [ICCV'25]
* **[2024.11.01]** **[Replace-then-Perturb: Targeted Adversarial Attacks With Visual Reasoning for Vision-Language Models](https://arxiv.org/abs/2411.00898v1)**
  * Jonggyu Jang, Hyeonsu Lyu, Jungyeon Koh, Hyun Jong Yang
  * Seoul National University, Pohang University of Science and Technology
  * [arXiv'24]
* **[2024.11.18]** **[Safe + Safe = Unsafe? Exploring How Safe Images Can Be Exploited to Jailbreak Large Vision-Language Models](https://arxiv.org/abs/2411.11496)** [![GitHub stars](https://img.shields.io/github/stars/matengsysu/himrd-jailbreak?style=social)](https://github.com/matengsysu/himrd-jailbreak)
  * Chenhang Cui, Gelei Deng, An Zhang, Jingnan Zheng, Yicong Li, Lianli Gao, Tianwei Zhang, Tat-Seng Chua
  * University of Electronic Science and Technology of China, National University of Singapore, Nanyang Technological University
  * [arXiv'24]
* **[2024.12.01]** **[Jailbreak Large Vision-Language Models Through Multi-Modal Linkage](https://arxiv.org/abs/2412.00473v4)** [![GitHub stars](https://img.shields.io/github/stars/gzcch/Safety_Snowball_Agent?style=social)](https://github.com/gzcch/Safety_Snowball_Agent)
  * Yu Wang, Xiaofei Zhou, Yichen Wang, Geyuan Zhang, Tianxing He
  * University of Chinese Academy of Sciences, Tsinghua University, Shanghai Qi Zhi Institute, University of Chicago
  * [CVPR'25]
* **[2024.12.08]** **[Heuristic-Induced Multimodal Risk Distribution Jailbreak Attack for Multimodal Large Language Models](https://arxiv.org/abs/2412.05934)** [![GitHub stars](https://img.shields.io/github/stars/matengsysu/himrd-jailbreak?style=social)](https://github.com/matengsysu/himrd-jailbreak)
  * Teng Ma, Xiaojun Jia, Ranjie Duan, Xinfeng Li, Yihao Huang, Xiaoshuang Jia, Zhixuan Chu, Wenqi Ren
  * Sun Yat-Sen University, Nanyang Technological University, Alibaba Group, Zhejiang University
  * [ICCV'25]
* **[2025.02.25]** **[Stealthy Backdoor Attack in Self-Supervised Learning Vision Encoders for Large Vision Language Models](https://arxiv.org/abs/2412.05934)**
  * Zhaoyi Liu, Huan Zhang
  * University of Illinois Urbana-Champaign
  * [CVPR'25]
* **[2025.03.20]** **[BadToken: Token-level Backdoor Attacks to Multi-modal Large Language Models](https://arxiv.org/abs/2503.16023)**
  * Zenghui Yuan, Jiawen Shi, Pan Zhou, Neil Zhenqiang Gong, Lichao Sun
  * Huazhong University of Science and Technology, Duke University, Lehigh University
  * [CVPR'25]
* **[2025.03.26]** [**Playing the Fool: Jailbreaking LLMs and Multimodal LLMs with Out-of-Distribution Strategy**](https://openaccess.thecvf.com/content/CVPR2025/html/Jeong_Playing_the_Fool_Jailbreaking_LLMs_and_Multimodal_LLMs_with_Out-of-Distribution_CVPR_2025_paper.html) [![GitHub stars](https://img.shields.io/github/stars/naver-ai/JOOD?style=social)](https://github.com/naver-ai/JOOD)
  * Joonhyun Jeong, Seyun Bae, Yeonsung Jung, Jaeryong Hwang, Eunho Yang
  * NAVER Cloud, Korea Advanced Institute of Science and Technology (KAIST), Republic of Korea Naval Academy, AITRICS
  * [CVPR'25]
* **[2025.10.09]** [**VisualDAN: Exposing Vulnerabilities in VLMs with Visual-Driven DAN Commands**](https://arxiv.org/abs/2510.09699)
  * Aofan Liu, Lulu Tang
  * Beijing Academy of Artificial Intelligence
  * [arXiv'25]


<h3 id="defenses"> <img src="assets/defense.png" alt="Icon" width="18" style="vertical-align:middle"/> Defenses </h3>

* **[2023.11.16]** **[DRESS: Instructing Large Vision-Language Models to Align and Interact with Humans via Natural Language Feedback](https://arxiv.org/abs/2311.10081)**
  * Yangyi Chen, Karan Sikka, Michael Cogswell, Heng Ji, Ajay Divakaran
  * SRI International, University of Illinois Urbana-Champaign
  * [CVPR'24]
* **[2023.12.17]** **[JailGuard: A Universal Detection Framework for LLM Prompt-based Attacks](https://arxiv.org/abs/2312.10766v4)** [![GitHub stars](https://img.shields.io/github/stars/shiningrain/JailGuard?style=social)](https://github.com/shiningrain/JailGuard)
  * Xiaoyu Zhang, Cen Zhang, Tianlin Li, Yihao Huang, Xiaojun Jia, Ming Hu, Jie Zhang, Yang Liu, Shiqing Ma, Chao Shen
  * Xi’an Jiaotong University, Nanyang Technological University, University of Massachusetts
  * [TOSEM'25]
* **[2024.01.05]** **[MLLM-Protector: Ensuring MLLM&#39;s Safety without Hurting Performance](https://arxiv.org/abs/2401.02906)** [![GitHub stars](https://img.shields.io/github/stars/pipilurj/MLLM-protector?style=social)](https://github.com/pipilurj/MLLM-protector)
  * Renjie Pi, Tianyang Han, Jianshu Zhang, Yueqi Xie, Rui Pan, Qing Lian, Hanze Dong, Jipeng Zhang, Tong Zhang
  * The Hong Kong University of Science and Technology, University of Illinois at Urbana-Champaign, The Hong Kong Polytechnic University
  * [EMNLP'24]
* **[2024.01.20]** **[InferAligner: Inference-Time Alignment for Harmlessness through Cross-Model Guidance](https://arxiv.org/abs/2401.11206)** [![GitHub stars](https://img.shields.io/github/stars/Jihuai-wpy/InferAligner?style=social)](https://github.com/Jihuai-wpy/InferAligner)
  * Pengyu Wang, Dong Zhang, Linyang Li, Chenkun Tan, Xinghao Wang, Ke Ren, Botian Jiang, Xipeng Qiu
  * Fudan University
  * [EMNLP'24]
* **[2024.02.03]** **[Safety Fine-Tuning at (Almost) No Cost: A Baseline for Vision Large Language Models](https://arxiv.org/abs/2402.02207)** [![GitHub stars](https://img.shields.io/github/stars/ys-zong/vlguard?style=social)](https://github.com/ys-zong/vlguard)
  * Yongshuo Zong, Ondrej Bohdal, Tingyang Yu, Yongxin Yang, Timothy Hospedales
  * University of Einburgh, EPFL
  * [ICML'24]
* **[2024.02.19]** **[Robust CLIP: Unsupervised Adversarial Fine-Tuning of Vision Embeddings for Robust Large Vision-Language Models](https://arxiv.org/abs/2402.12336)** [![GitHub stars](https://img.shields.io/github/stars/chs20/robustvlm?style=social)](https://github.com/chs20/robustvlm)
  * Christian Schlarmann, Naman Deep Singh, Francesco Croce, Matthias Hein
  * Tübingen AI Center, University of Tübingen, EPFL
  * [ICML'24]
* **[2024.03.14]** **[Eyes Closed, Safety On: Protecting Multimodal LLMs via Image-to-Text Transformation](https://arxiv.org/abs/2403.09572)** [![GitHub stars](https://img.shields.io/github/stars/gyhdog99/ECSO?style=social)](https://github.com/gyhdog99/ECSO)
  * Yunhao Gou, Kai Chen, Zhili Liu, Lanqing Hong, Hang Xu, Zhenguo Li, Dit-Yan Yeung, James T. Kwok, Yu Zhang
  * Southern University of Science and Technology, Hong Kong University of Science and Technology, Huawei Noah’s Ark Lab
  * [ECCV'24]
* **[2024.03.14**] **[AdaShield: Safeguarding Multimodal Large Language Models from Structure-based Attack via Adaptive Shield Prompting](https://arxiv.org/abs/2403.09513)** [![GitHub stars](https://img.shields.io/github/stars/SaFoLab-WISC/AdaShield?style=social)](https://github.com/SaFoLab-WISC/AdaShield)
  * Yu Wang, Xiaogeng Liu, Yu Li, Muhao Chen, Chaowei Xiao
  * Peking University, University of Wisconsin–Madison, International Digital Economy Academy, University of California, Davis
  * [ECCV'24]
* **[2024.05.17]** **[Safeguarding Vision-Language Models Against Patched Visual Prompt Injectors](https://arxiv.org/abs/2405.10529)**
  * Jiachen Sun, Changsheng Wang, Jiongxiao Wang, Yiwei Zhang, Chaowei Xiao
  * University of Michigan Ann arbor, University of Wisconsin Madison, Michigan State University
  * [arXiv'24]
* **[2024.05.21]** **[Single Image Unlearning: Efficient Machine Unlearning in Multimodal Large Language Models](https://arxiv.org/abs/2405.12523)**
  * Jiaqi Li, Qianshan Wei, Chuanyi Zhang, Guilin Qi, Miaozeng Du, Yongrui Chen, Sheng Bi
  * Southeast University, Hohai University
  * [NeurIPS'24]
* **[2024.05.22]** **[Safety Alignment for Vision Language Models](https://arxiv.org/abs/2405.13581)**
  * Zhendong Liu, Yuanbi Nie, Yingshui Tan, Xiangyu Yue, Qiushi Cui, Chongjun Wang, Xiaoyong Zhu, Bo Zheng
  * Nanjing University, Chongqing University, Alibaba Group, Chinese University of Hong Kong
  * [arXiv'24]
* **[2024.05.27]** **[Cross-Modal Safety Alignment: Is textual unlearning all you need?](https://arxiv.org/abs/2406.02575)**
  * Trishna Chakraborty, Erfan Shayegani, Zikui Cai, Nael Abu-Ghazaleh, M. Salman Asif, Yue Dong, Amit K. Roy-Chowdhury, Chengyu Song
  * University of California, Riverside
  * [EMNLP'24 Findings]
* **[2024.06.07]** **[LLavaGuard: VLM-based Safeguards for Vision Dataset Curation and Safety Assessment](https://arxiv.org/abs/2406.05113)** [![GitHub stars](https://img.shields.io/github/stars/ml-research/llavaguard?style=social)](https://github.com/ml-research/llavaguard)
  * Lukas Helff, Felix Friedrich, Manuel Brack, Kristian Kersting, Patrick Schramowski
  * Technical University of Darmstadt, hessian.AI, DFKI, Centre for Cognitive Science, Ontocord
  * [ICML'25]
* **[2024.06.13]** **[MirrorCheck: Efficient Adversarial Defense for Vision-Language Models](https://arxiv.org/abs/2406.09250)**
  * Samar Fares, Klea Ziu, Toluwani Aremu, Nikita Durasov, Martin Takáč, Pascal Fua, Karthik Nandakumar, Ivan Laptev
  * Mohamed bin Zayed University of Artificial Intelligence, EPFL
  * [arXiv'24]
* **[2024.06.17]** **[SPA-VL: A Comprehensive Safety Preference Alignment Dataset for Vision Language Model](https://arxiv.org/abs/2406.12030)** [![GitHub stars](https://img.shields.io/github/stars/echosechen/spa-vl-rlhf?style=social)](https://github.com/echosechen/spa-vl-rlhf)
  * Yongting Zhang, Lu Chen, Guodong Zheng, Yifeng Gao, Rui Zheng, Jinlan Fu, Zhenfei Yin, Senjie Jin, Yu Qiao, Xuanjing Huang, Feng Zhao, Tao Gui, Jing Shao
  * University of Science and Technology of China, Fudan University, Shanghai Artificial Intelligence Laboratory
  * [CVPR'25]
* **[2024.07.20]** **[Sim-CLIP: Unsupervised Siamese Adversarial Fine-Tuning for Robust and Semantically-Rich Vision-Language Models](https://arxiv.org/abs/2407.14971v2)** [![GitHub stars](https://img.shields.io/github/stars/speedlab-git/SimCLIP?style=social)](https://github.com/speedlab-git/SimCLIP)
  * Md Zarif Hossain, Ahmed Imteaj
  * Southern Illinois University, Security, Privacy and Intelligence for Edge Devices Laboratory
  * [arXiv'24]
* **[2024.07.31]** **[Cross-modality Information Check for Detecting Jailbreaking in Multimodal Large Language Models](https://arxiv.org/abs/2407.21659v4)** [![GitHub stars](https://img.shields.io/github/stars/pandragonxiii/cider?style=social)](https://github.com/pandragonxiii/cider)
  * Yue Xu, Xiuyuan Qi, Zhan Qin, Wenjie Wang
  * ShanghaiTech University, Zhejiang University
  * [EMNLP'24]
* **[2024.08.17]** **[BaThe: Defense against the Jailbreak Attack in Multimodal Large Language Models by Treating Harmful Instruction as Backdoor Trigger](https://arxiv.org/abs/2408.09093)**
  * Yulin Chen, Haoran Li, Yirui Zhang, Zihao Zheng, Yangqiu Song, Bryan Hooi
  * National University of Singapore, Hong Kong University of Science and Technology, Harbin Institute of Technology, Shenzhen
  * [arXiv'24]
* **[2024.09.08]** **[PIP: Detecting Adversarial Examples in Large Vision-Language Models via Attention Patterns of Irrelevant Probe Questions](https://www.arxiv.org/abs/2409.05076)**
  * Yudong Zhang, Ruobing Xie, Jiansheng Chen, Xingwu Sun, Yu Wang
  * Tsinghua University, Tencent, University of Science and Technology Beijing
  * [MM'24]
* **[2024.09.11]** **[Sim-CLIP+: Securing Vision-Language Models with a Robust Encoder Against Jailbreak and Adversarial Attacks](https://arxiv.org/abs/2409.07353)**
  * Md Zarif Hossain, Ahmed Imteaj
  * Southern Illinois University, Security, Privacy and Intelligence for Edge Devices Laboratory
  * [BigData'24]
* **[2024.09.17]** **[CoCA: Regaining Safety-awareness of Multimodal Large Language Models with Constitutional Calibration](https://arxiv.org/abs/2409.11365)**
  * Jiahui Gao, Renjie Pi, Tianyang Han, Han Wu, Lanqing Hong, Lingpeng Kong, Xin Jiang, Zhenguo Li
  * Noah’s Ark Lab, The Hong Kong University of Science and Technology, The Hong Kong Polytechnic University, The University of Hong Kong
  * [COLM'24]
* **[2024.10.01]** **[VLMGuard: Defending VLMs against Malicious Prompts via Unlabeled Data](https://arxiv.org/abs/2410.00296v1)**
  * Xuefeng Du, Reshmi Ghosh, Robert Sim, Ahmed Salem, Vitor Carvalho, Emily Lawton, Yixuan Li, Jack W. Stokes
  * University of Wisconsin-Madison, Microsoft Corp
  * [arXiv'24]
* **[2024.10.09]** **[ETA: Evaluating Then Aligning Safety of Vision Language Models at Inference Time](https://arxiv.org/abs/2410.06625)** [![GitHub stars](https://img.shields.io/github/stars/dripnowhy/eta?style=social)](https://github.com/dripnowhy/eta)
  * Yi Ding, Bolian Li, Ruqi Zhang
  * Purdue University
  * [ICLR'25]
* **[2024.10.11]** **[Unraveling and Mitigating Safety Alignment Degradation of Vision-Language Models](https://arxiv.org/abs/2410.09047)**
  * Qin Liu, Chao Shang, Ling Liu, Nikolaos Pappas, Jie Ma, Neha Anna John, Srikanth Doss, Lluis Marquez, Miguel Ballesteros, Yassine Benajiba
  * University of California, Davis, AWS AI Labs
  * [arXiv'24]
* **[2024.10.16]** **[Cross-Modal Safety Mechanism Transfer in Large Vision-Language Models](https://arxiv.org/abs/2410.12662)**
  * Shicheng Xu, Liang Pang, Yunchang Zhu, Huawei Shen, Xueqi Cheng
  * Institute of Computing Technology
  * [ICLR'25]
* **[2024.10.28]** **[BlueSuffix: Reinforced Blue Teaming for Vision-Language Models Against Jailbreak Attacks](https://arxiv.org/abs/2410.20971)**
  * Yunhan Zhao, Xiang Zheng, Lin Luo, Yige Li, Xingjun Ma, Yu-Gang Jiang
  * Fudan University, City University of Hong Kong, Singapore Management University
  * [ICLR'25]
* **[2024.10.30]** **[Effective and Efficient Adversarial Detection for Vision-Language Models via A Single Vector](https://arxiv.org/abs/2410.22888)** [![GitHub stars](https://img.shields.io/github/stars/mob-scu/radar-nearside?style=social)](https://github.com/mob-scu/radar-nearside)
  * Youcheng Huang, Fengbin Zhu, Jingkun Tang, Pan Zhou, Wenqiang Lei, Jiancheng Lv, Tat-Seng Chua
  * Sichuan University, National University of Singapore, Singapore Management University
  * [arXiv'24]
* **[2024.11.03]** **[UniGuard: Towards Universal Safety Guardrails for Jailbreak Attacks on Multimodal Large Language Models](https://arxiv.org/abs/2411.01703)**
  * Sejoon Oh, Yiqiao Jin, Megha Sharma, Donghyun Kim, Eric Ma, Gaurav Verma, Srijan Kumar
  * Netflix, Georgia Institute of Technology
  * [arXiv'24]
* **[2024.11.15]** **[Llama Guard 3 Vision: Safeguarding Human-AI Image Understanding Conversations](https://arxiv.org/abs/2411.10414)**
  * Jianfeng Chi, Ujjwal Karn, Hongyuan Zhan, Eric Smith, Javier Rando, Yiming Zhang, Kate Plawiak, Zacharie Delpierre Coudert, Kartikeya Upasani, Mahesh Pasupuleti
  * Meta
  * [arXiv'24]
* **[2024.11.23]** **[Steering Away from Harm: An Adaptive Approach to Defending Vision Language Model Against Jailbreaks](https://arxiv.org/abs/2411.16721)** [![GitHub stars](https://img.shields.io/github/stars/ASTRAL-Group/ASTRA?style=social)](https://github.com/ASTRAL-Group/ASTRA)
  * Han Wang, Gang Wang, Huan Zhang
  * University of Illinois Urbana-Champaign
  * [CVPR'25]
* **[2024.11.27]** **[Immune: Improving Safety Against Jailbreaks in Multi-modal LLMs via Inference-Time Alignment](https://arxiv.org/abs/2411.18688)** [![GitHub stars](https://img.shields.io/github/stars/itsvaibhav01/Immune?style=social)](https://github.com/itsvaibhav01/Immune)
  * Soumya Suvra Ghosal, Souradip Chakraborty, Vaibhav Singh, Tianrui Guan, Mengdi Wang, Ahmad Beirami, Furong Huang, Alvaro Velasquez, Dinesh Manocha, Amrit Singh Bedi
  * University of Maryland, Indian Institute of Technology Bombay, Princeton University, University of Colorado Boulder, University of Central Florida
  * [arXiv'24]
* **[2024.12.17]** **[Defending LVLMs Against Vision Attacks through Partial-Perception Supervision](https://arxiv.org/abs/2412.12722)** [![GitHub stars](https://img.shields.io/github/stars/tools-only/DPS?style=social)](https://github.com/tools-only/DPS)
  * Qi Zhou, Dongxia Wang, Tianlin Li, Yun Lin, Yang Liu, Jin Song Dong, Qing Guo
  * Zhejiang University, Nanyang Technological University, A*STAR, Shanghai Jiao Tong University, National University of Singapore
  * [ICML'25]
* **[2025.01.30]** **[Rethinking Bottlenecks in Safety Fine-Tuning of Vision Language Models](https://arxiv.org/abs/2501.18533v1)** [![GitHub stars](https://img.shields.io/github/stars/DripNowhy/MIS?style=social)](https://github.com/DripNowhy/MIS)
  * Yi Ding, Lijun Li, Bing Cao, Jing Shao
  * Shanghai Artificial Intelligence Laboratory, Tianjin University
  * [arXiv'25]
* **[2025.02.14]** **[VLM-Guard: Safeguarding Vision-Language Models via Fulfilling Safety Alignment Gap](https://arxiv.org/abs/2502.10486)**
  * Qin Liu, Fei Wang, Chaowei Xiao, Muhao Chen
  * UC Davis, USC, UW-Madison
  * [arXiv'25]
* **[2025.02.17]** **[Adversary-Aware DPO: Enhancing Safety Alignment in Vision Language Models via Adversarial Training](https://arxiv.org/abs/2502.11455)**
  * Fenghua Weng, Jian Lou, Jun Feng, Minlie Huang, Wenjie Wang
  * ShanghaiTech University, Sun Yat-Sen University, Huazhong University of Science and Technology, Tsinghua University
  * [arXiv'25]
* **[2025.02.18]** **[SEA: Low-Resource Safety Alignment for Multimodal Large Language Models via Synthetic Embeddings](https://arxiv.org/abs/2502.12562)**
  * Weikai Lu, Hao Peng, Huiping Zhuang, Cen Chen, Ziqian Zeng
  * South China University of Technology, Beihang University, Pazhou Laboratory
  * [ACL'25]
* **[2025.02.20]** **[How Jailbreak Defenses Work and Ensemble? A Mechanistic Investigation](https://arxiv.org/abs/2502.14486)**
  * Zhuohang Long, Siyuan Wang, Shujun Liu, Yuhang Lai, Xuanjing Huang, Zhongyu Wei
  * Fudan University, University of Southern California
  * [arXiv'25]
* **[2025.02.20]** **[HiddenDetect: Detecting Jailbreak Attacks against Large Vision-Language Models via Monitoring Hidden States](https://arxiv.org/abs/2502.14744)** [![GitHub stars](https://img.shields.io/github/stars/leigest519/HiddenDetect?style=social)](https://github.com/leigest519/HiddenDetect)
  * Yilei Jiang, Xinyan Gao, Tianshuo Peng, Yingshui Tan, Xiaoyong Zhu, Bo Zheng, Xiangyu Yue
  * The Chinese University of Hong Kong, Alibaba Group
  * [ACL'25]
* **[2025.03.05]** **[Adversarial Training for Multimodal Large Language Models against Jailbreak Attacks](https://arxiv.org/abs/2503.04833)**
  * Liming Lu, Shuchao Pang, Siyuan Liang, Haotian Zhu, Xiyu Zeng, Aishan Liu, Yunhuai Liu, Yongbin Zhou
  * Nanjing University of Science and Technology, National University of Singapore, Beihang University
  * [arXiv'25]
* **[2025.03.22]** **[Safe RLHF-V: Safe Reinforcement Learning from Human Feedback in Multimodal Large Language Models](https://arxiv.org/abs/2503.17682)** [![GitHub stars](https://img.shields.io/github/stars/saferlhf-v/saferlhf-v?style=social)](https://github.com/saferlhf-v/saferlhf-v)
  * Jiaming Ji, Xinyu Chen, Rui Pan, Han Zhu, Conghui Zhang, Jiahao Li, Donghai Hong, Boyuan Chen, Jiayi Zhou, Kaile Wang, Juntao Dai, Chi-Min Chan, Sirui Han, Yike Guo, Yaodong Yang
  * Peking University, Hong Kong University of Science and Technology
  * [arXiv'25]
* **[2025.04.03]** [**JailDAM: Jailbreak Detection with Adaptive Memory for Vision-Language Model**](https://arxiv.org/abs/2504.03770) [![GitHub stars](https://img.shields.io/github/stars/ShenzheZhu/JailDAM?style=social)](https://github.com/ShenzheZhu/JailDAM)
  * Yi Nian, Shenzhe Zhu, Yuehan Qin, Li Li, Ziyi Wang, Chaowei Xiao, Yue Zhao
  * University of Southern California, University of Toronto, University of Maryland, University of Wisconsin-Madison
  * [COLM'25]
* **[2025.04.17]** **[VLMGuard-R1: Proactive Safety Alignment for VLMs via Reasoning-Driven Prompt Optimization](https://www.arxiv.org/abs/2504.12661)**
  * Menglan Chen, Xianghe Pang, Jingjing Dong, WenHao Wang, Yaxin Du, Siheng Chen
  * Shanghai Jiao Tong University
  * [arXiv'25]
* **[2025.04.25]** **[DREAM: Disentangling Risks to Enhance Safety Alignment in Multimodal Large Language Models](https://arxiv.org/abs/2504.18053)**
  * Jianyu Liu, Hangyu Guo, Ranjie Duan, Xingyuan Bu, Yancheng He, Shilong Li, Hui Huang, Jiaheng Liu, Yucheng Wang, Chenchen Jing, Xingwei Qu, Xiao Zhang, Yingshui Tan, Yanan Wu, Jihao Gu, Yangguang Li, Jianke Zhu
  * Alibaba Group, Zhejiang University, M-A-P, The Chinese University of Hong Kong
  * [arXiv'25]
* **[2025.05.22]** **[Backdoor Cleaning without External Guidance in MLLM Fine-tuning](https://arxiv.org/abs/2505.16916)**
  * Xuankun Rong, Wenke Huang, Jian Liang, Jinhe Bi, Xun Xiao, Yiming Li, Bo Du, Mang Ye
  * Wuhan University, Munich Research Center Huawei Technologies, Nanyang Technological University
  * [NeurIPS'25]
* **[2025.06.11]** **[HoliSafe: Holistic Safety Benchmarking and Modeling with Safety Meta Token for Vision-Language Model](https://www.arxiv.org/abs/2506.04704)**
  * Youngwan Lee, Kangsan Kim, Kwanyong Park, Ilcahe Jung, Soojin Jang, Seanie Lee, Yong-Ju Lee, Sung Ju Hwang
  * ETRI, KAIST AI, University of Seoul, DeepAuto
  * [arXiv'25]
* **[2025.12.02]** **[OmniGuard: Unified Omni-Modal Guardrails with Deliberate Reasoning](https://arxiv.org/abs/2512.02306)**
  * Boyu Zhu, Xiaofei Wen, Wenjie Jacky Mo, Tinghui Zhu, Yanan Xie, Peng Qi, Muhao Chen
  * Fudan University, UC Davis, Uniphore
  * [arXiv'25]
* **[2025.12.12]** **[Rethinking Jailbreak Detection of Large Vision Language Models with Representational Contrastive Scoring](https://arxiv.org/abs/2512.12069)** [![GitHub stars](https://img.shields.io/github/stars/sarendis56/Jailbreak_Detection_RCS)](https://github.com/sarendis56/Jailbreak_Detection_RCS)
  * Peichun Hua, Hao Li, Shanghao Shi, Zhiyuan Yu, Ning Zhang
  * Washington University in St. Louis, Texas A&M University
  * [arXiv'25]
* **[2026.02.03]** **[GuardReasoner-Omni: A Reasoning-based Multi-modal Guardrail for Text, Image, and Video](https://arxiv.org/abs/2602.03328)**
  * Zhenhao Zhu, Yue Liu, Yanpei Guo, Wenjie Qu, Cancan Chen, Yufei He, Yibo Li, Yulin Chen, Tianyi Wu, Huiying Xu, Xinzhong Zhu, Jiaheng Zhang
  * Tsinghua University, National University of Singapore, Sun Yat-sen University, Zhejiang Normal University
  * [arXiv'26]
<h3 id="evaluations"> <img src="assets/evaluation.png" alt="Icon" width="27" style="vertical-align:middle"/> Evaluations </h3>

* **[2023.11.27]** **[How Many Unicorns Are in This Image? A Safety Evaluation Benchmark for Vision LLMs](https://arxiv.org/abs/2311.16101)** [![GitHub stars](https://img.shields.io/github/stars/UCSC-VLAA/vllm-safety-benchmark?style=social)](https://github.com/UCSC-VLAA/vllm-safety-benchmark)
  * Haoqin Tu, Chenhang Cui, Zijun Wang, Yiyang Zhou, Bingchen Zhao, Junlin Han, Wangchunshu Zhou, Huaxiu Yao, Cihang Xie
  * UC Santa Cruz, UNC-Chapel Hill, University of Edinburgh , University of Oxford, AIWaves Inc.
  * [ECCV'24]
* **[2023.11.29]** **[MM-SafetyBench: A Benchmark for Safety Evaluation of Multimodal Large Language Models](https://arxiv.org/abs/2311.17600)** [![GitHub stars](https://img.shields.io/github/stars/isxinliu/mm-safetybench?style=social)](https://github.com/isxinliu/mm-safetybench)
  * Xin Liu, Yichen Zhu, Jindong Gu, Yunshi Lan, Chao Yang, Yu Qiao
  * Shanghai AI Laboratory, East China Normal University, Midea Group, University of Oxford
  * [ECCV'24]
* **[2024.01.23]** **[Red Teaming Visual Language Models](https://arxiv.org/abs/2401.12915)** [![GitHub stars](https://img.shields.io/github/stars/kiaia/RedTeamVLM?style=social)](https://github.com/kiaia/RedTeamVLM)
  * Mukai Li, Lei Li, Yuwei Yin, Masood Ahmed, Zhenguang Liu, Qi Liu
  * The University of Hong Kong, Zhejiang University
  * [ACL'24]
* **[2024.02.29]** **[Unveiling Typographic Deceptions: Insights of the Typographic Vulnerability in Large Vision-Language Model](https://arxiv.org/abs/2402.19150)** [![GitHub stars](https://img.shields.io/github/stars/ChaduCheng/TypoDeceptions?style=social)](https://github.com/ChaduCheng/TypoDeceptions)
  * Hao Cheng, Erjia Xiao, Jindong Gu, Le Yang, Jinhao Duan, Jize Zhang, Jiahang Cao, Kaidi Xu, Renjing Xu
  * The Hong Kong University of Science and Technology (Guangzhou), University of Oxford, Xi’an Jiaotong University, Drexel University, The Hong Kong University of Science and Technology
  * [ECCV'24]
* **[2024.03.14]** **[AVIBench: Towards Evaluating the Robustness of Large Vision-Language Model on Adversarial Visual-Instructions](https://arxiv.org/abs/2403.09346)** [![GitHub stars](https://img.shields.io/github/stars/zhanghao5201/b-avibench?style=social)](https://github.com/zhanghao5201/b-avibench)
  * Hao Zhang, Wenqi Shao, Hong Liu, Yongqiang Ma, Ping Luo, Yu Qiao, Nanning Zheng, Kaipeng Zhang
  * Xi’an Jiaotong University, Shanghai Artificial Intelligence Laboratory, Osaka University
  * [arXiv'24]
* **[2024.04.03]** **[JailBreakV-28K: A Benchmark for Assessing the Robustness of MultiModal Large Language Models against Jailbreak Attacks](https://arxiv.org/abs/2404.03027)** [![GitHub stars](https://img.shields.io/github/stars/EddyLuo1232/JailBreakV_28K?style=social)](https://github.com/EddyLuo1232/JailBreakV_28K)
  * Weidi Luo, Siyuan Ma, Xiaogeng Liu, Xiaoyu Guo, Chaowei Xiao
  * The Ohio State University, Peking University, University of Wisconsin-Madison
  * [COLM'24]
* **[2024.04.04]** **[Red Teaming GPT-4V: Are GPT-4V Safe Against Uni/Multi-Modal Jailbreak Attacks?](https://arxiv.org/abs/2404.03411)** [![GitHub stars](https://img.shields.io/github/stars/chenxshuo/redteaminggpt4v?style=social)](https://github.com/chenxshuo/redteaminggpt4v)
  * Shuo Chen, Zhen Han, Bailan He, Zifeng Ding, Wenqian Yu, Philip Torr, Volker Tresp, Jindong Gu
  * LMU Munich, University of Oxford, Siemens AG, Munich Center for Machine Learning (MCML), Wuhan University
  * [ICLR'24]
* **[2024.06.11]** **[MultiTrust: A Comprehensive Benchmark Towards Trustworthy Multimodal Large Language Models](https://arxiv.org/abs/2406.07057)** [![GitHub stars](https://img.shields.io/github/stars/thu-ml/MMTrustEval?style=social)](https://github.com/thu-ml/MMTrustEval)
  * Yichi Zhang, Yao Huang, Yitong Sun, Chang Liu, Zhe Zhao, Zhengwei Fang, Yifan Wang, Huanran Chen, Xiao Yang, Xingxing Wei, Hang Su, Yinpeng Dong, Jun Zhu
  * Tsinghua University,  Beihang University, Shanghai Jiao Tong University, RealAI, Pazhou Lab (Huangpu)
  * [NeurIPS'24]
* **[2024.06.11]** **[MLLMGuard: A Multi-dimensional Safety Evaluation Suite for Multimodal Large Language Models](https://arxiv.org/abs/2406.07594)** [![GitHub stars](https://img.shields.io/github/stars/AI45Lab/MLLMGuard?style=social)](https://github.com/AI45Lab/MLLMGuard)
  * Tianle Gu, Zeyang Zhou, Kexin Huang, Dandan Liang, Yixu Wang, Haiquan Zhao, Yuanqi Yao, Xingge Qiao, Keqing Wang, Yujiu Yang, Yan Teng, Yu Qiao, Yingchun Wang
  * Tsinghua Shenzhen International Graduate School, Shanghai Artificial Intelligence Laboratory
  * [NeurIPS'24]
* **[2024.06.21]** **[Cross-Modality Safety Alignment](https://arxiv.org/abs/2406.15279)** [![GitHub stars](https://img.shields.io/github/stars/sinwang20/siuo?style=social)](https://github.com/sinwang20/siuo)
  * Siyin Wang, Xingsong Ye, Qinyuan Cheng, Junwen Duan, Shimin Li, Jinlan Fu, Xipeng Qiu, Xuanjing Huang
  * Fudan University, National University of Singapore, Shanghai AI Laboratory
  * [NAACL'25]
* **[2024.06.22]** **[MOSSBench: Is Your Multimodal Language Model Oversensitive to Safe Queries?](https://arxiv.org/abs/2406.17806)** [![GitHub stars](https://img.shields.io/github/stars/xirui-li/MOSSBench?style=social)](https://github.com/xirui-li/MOSSBench)
  * Xirui Li, Hengguang Zhou, Ruochen Wang, Tianyi Zhou, Minhao Cheng, Cho-Jui Hsieh
  * University of California, LA,  University of Maryland, Pennsylvania State University
  * [ICLR'25]
* **[2024.07.21]** **[Arondight: Red Teaming Large Vision Language Models with Auto-generated Multi-modal Jailbreak Prompts](https://arxiv.org/abs/2407.15050)**
  * Yi Liu, Chengjun Cai, Xiaoli Zhang, Xingliang Yuan, Cong Wang
  * City University of Hong Kong, University of Science and Technology, The University of Melbourne
  * [MM'24]
* **[2024.08.15]** **[MMJ-Bench: A Comprehensive Study on Jailbreak Attacks and Defenses for Multimodal Large Language Models](https://arxiv.org/abs/2408.08464)** [![GitHub stars](https://img.shields.io/github/stars/thunxxx/MLLM-Jailbreak-evaluation-MMJ-bench?style=social)](https://github.com/thunxxx/MLLM-Jailbreak-evaluation-MMJ-bench)
  * Fenghua Weng, Yue Xu, Chengyan Fu, Wenjie Wang
  * ShanghaiTech University
  * [arXiv'24]
* **[2024.10.08]** **[Multimodal Situational Safety](https://arxiv.org/abs/2410.06172)** [![GitHub stars](https://img.shields.io/github/stars/eric-ai-lab/MSSBench?style=social)](https://github.com/eric-ai-lab/MSSBench)
  * Kaiwen Zhou, Chengzhi Liu, Xuandong Zhao, Anderson Compalas, Dawn Song, Xin Eric Wang
  * University of California, Santa Cruz, University of California, Berkeley
  * [ICLR'25]
* **[2024.10.24]** **[SafeBench: A Safety Evaluation Framework for Multimodal Large Language Models](https://arxiv.org/abs/2410.18927)**
  * Zonghao Ying, Aishan Liu, Siyuan Liang, Lei Huang, Jinyang Guo, Wenbo Zhou, Xianglong Liu, Dacheng Tao
  * Beihang University, National University of Singapore, Zhongguancun Laboratory, Hefei Comprehensive National Science Center, University of Science and Technology of China, Nanyang Technological University, Singapore
  * [arXiv'24]
* **[2024.11.29]** **[VLSBench: Unveiling Visual Leakage in Multimodal Safety](https://arxiv.org/abs/2411.19939)** [![GitHub stars](https://img.shields.io/github/stars/AI45Lab/VLSBench?style=social)](https://github.com/AI45Lab/VLSBench)
  * Xuhao Hu, Dongrui Liu, Hao Li, Xuanjing Huang, Jing Shao
  * Shanghai Artificial Intelligence Laboratory, Fudan University, Beihang University
  * [arXiv'24]
* **[2025.05.21]** **[Are Vision-Language Models Safe in the Wild? A Meme-Based Benchmark Study](https://arxiv.org/abs/2505.15389)** [![GitHub stars](https://img.shields.io/github/stars/oneonlee/meme-safety-bench?style=social)](https://github.com/oneonlee/meme-safety-bench)
  * DongGeon Lee, Joonwon Jang, Jihae Jeong, Hwanjo Yu
  * POSTECH, LG AI Research
  * [EMNLP'25]
* **[2025.05.16]** **[GuardReasoner-VL: Safeguarding VLMs via Reinforced Reasoning](https://arxiv.org/abs/2505.11049)** [![GitHub stars](https://img.shields.io/github/stars/yueliu1999/GuardReasoner-VL?style=social)](https://github.com/yueliu1999/GuardReasoner-VL)
  * Yue Liu, Shengfang Zhai, Mingzhe Du, Yulin Chen, Tri Cao, Hongcheng Gao, Cheng Wang, Xinfeng Li, Kun Wang, Junfeng Fang, Jiaheng Zhang, Bryan Hooi
  * NUS, NTU
  * [NeurIPS'25]
* **[2025.06.11]** **[HoliSafe: Holistic Safety Benchmarking and Modeling with Safety Meta Token for Vision-Language Model](https://www.arxiv.org/abs/2506.04704)**
  * Youngwan Lee, Kangsan Kim, Kwanyong Park, Ilcahe Jung, Soojin Jang, Seanie Lee, Yong-Ju Lee, Sung Ju Hwang
  * ETRI, KAIST AI, University of Seoul, DeepAuto
  * [arXiv'25]

<h2 id="januspro"> 🤖 Evaluation on Janus-Pro </h2>

Janus-Pro-7B is the latest LVLM released by DeepSeek, representing a significant advancement over Janus-1B. This new model scales up both the data and model parameters, validating the potential of the original design. DeepSeek’s Janus-Pro integrates unified multimodal understanding and generation capabilities, addressing the longstanding gap between image understanding and image generation. However, given its strong multimodel understanding performance, how about Janus-Pro’s safety capability?

We conduct a set of safety evaluations on Janus-Pro, utilizing two open-source benchmarks: SIUO and MM-SafetyBench.

<p>Evaluation on SIUO using ASR (↓) with both close-source and open-source LVLMs. OpenQA refers to open-ended question answering, while MCQA refers to multiple-choice question answering.</p>

<div align="center">
<img width="35%" alt="SIUO" src="assets/Januspro_SIUO.png">
</div>

<p>Evaluation on MM-SafetyBench using ASR (↓) for LLaVA-1.5-7B, LLaVA-1.5-13B, and Janus-Pro-7B, highlighting the <strong>best</strong> and <ins>second-best</ins> performances.</p>

<div align="center">
<img width="65%" alt="MMSafetyBench" src="assets/Januspro_MMSafetyBench.png">
</div>

<h2 id="contact"> 👋 Contact </h2>

This repository is currently maintained by [Xuankun Rong](https://xuankunrong.github.io/) 👨‍💻. If you have any questions, concerns, or suggestions regarding the contents of this repository or the resources shared here, feel free to reach out! I'm more than happy to assist you with any inquiries or help you navigate through the materials. Please don't hesitate to send an email to me at [rongxuankun@whu.edu.cn](mailto:rongxuankun@whu.edu.cn) 📧, and I will get back to you as soon as possible. Let's keep improving the **LVLM Safety** community together! 🚀

Looking forward to hearing from you! 😊

<h2 id="citation"> 🥳 Citation </h2>

Please kindly cite this paper in your publications if it helps your research:

```bibtex
@article{SafetySurvey,
  title={A survey of safety on large vision-language models: Attacks, defenses and evaluations},
  author={Ye, Mang and Rong, Xuankun and Huang, Wenke and Du, Bo and Yu, Nenghai and Tao, Dacheng},
  journal={arXiv preprint arXiv:2502.14881},
  year={2025}
}
```
