<h1 align="center">Awesome Controllable Generation</h1>

<p align="center">
    <img src="https://awesome.re/badge.svg" href="https://github.com/atfortes/Awesome-Controllable-Generation"/>
    <img src="https://img.shields.io/badge/License-MIT-green.svg" href="https://opensource.org/licenses/MIT"/>
    <img src="https://img.shields.io/badge/PRs-Welcome-red"/>
    <img src="https://img.shields.io/github/last-commit/atfortes/Awesome-Controllable-Generation?color=green"/>
</p>

<p align="center">
    <b> Papers and Resources on Adding Conditional Controls to Deep Generative Models in the Era of AIGC.</b>
</p>

<p align="center">
     Dive into the cutting-edge of controllable generation in diffusion models, a field revolutionized by pioneering works like ControlNet <a href=https://arxiv.org/abs/2302.05543>[1]</a> and DreamBooth <a href=https://arxiv.org/abs/2302.05543>[2]</a>. This repository is invaluable for those interested in advanced techniques for fine-grained synthesis control, ranging from subject-driven generation to intricate layout manipulations. While ControlNet and DreamBooth are key highlights, the collection spans a broader spectrum, including recent advancements and applications in image, video, and 3D generation.
</p>

<p align="center">
    <i>Updated daily</i>
</p>



## Contents



- [Papers](#papers)
  - [Diffusion Models](#diffusion-models)
  - [Consistency Models](#consistency-models)
- [Other Resources](#other-resources)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)


 
## Papers



### Diffusion Models


 
- **[DreamBooth: Fine Tuning Text-to-Image Diffusion Models for Subject-Driven Generation.](https://arxiv.org/abs/2208.12242)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Subject--Driven-orange?style=flat-square)

    *Nataniel Ruiz, Yuanzhen Li, Varun Jampani, Yael Pritch, Michael Rubinstein, Kfir Aberman.* CVPR'23. 🔥
  
    <img src="assets/dreambooth.png" style="width:100%">

- **[Adding Conditional Control to Text-to-Image Diffusion Models.](https://arxiv.org/abs/2302.05543)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Layout-a50b5e?style=flat-square)

    *Lvmin Zhang, Anyi Rao, Maneesh Agrawala.* ICCV'23. 🔥

    <img src="assets/controlnet.png" style="width:100%">

- **[T2I-Adapter: Learning Adapters to Dig out More Controllable Ability for Text-to-Image Diffusion Models.](https://arxiv.org/abs/2302.08453)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Layout-a50b5e?style=flat-square)

    *Chong Mou, Xintao Wang, Liangbin Xie, Yanze Wu, Jian Zhang, Zhongang Qi, Ying Shan, Xiaohu Qie.* Preprint 2023. 🔥

    <img src="assets/t2i-adapter.png" style="width:100%">

- **[Subject-driven Text-to-Image Generation via Apprenticeship Learning.](https://arxiv.org/abs/2304.00186)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Subject--Driven-orange?style=flat-square)

    *Wenhu Chen, Hexiang Hu, Yandong Li, Nataniel Ruiz, Xuhui Jia, Ming-Wei Chang, William W. Cohen.* NeurIPS'23.

- **[InstantBooth: Personalized Text-to-Image Generation without Test-Time Finetuning.](https://arxiv.org/abs/2304.03411)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Subject--Driven-orange?style=flat-square)

    *Jing Shi, Wei Xiong, Zhe Lin, Hyun Joon Jung.* Preprint 2023.

- **[BLIP-Diffusion: Pre-trained Subject Representation for Controllable Text-to-Image Generation and Editing](https://arxiv.org/abs/2305.14720)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Subject--Driven-orange?style=flat-square)

    *Dongxu Li, Junnan Li, Steven C.H. Hoi.* NeurIPS'23. 🔥

    <img src="assets/blip-diffusion.png" style="width:100%">

- **[ControlVideo: Conditional Control for One-shot Text-driven Video Editing and Beyond.](https://arxiv.org/abs/2305.17098)**

    ![](https://img.shields.io/badge/Video-9370db?style=flat-square)![](https://img.shields.io/badge/Layout-a50b5e?style=flat-square)

    *Min Zhao, Rongzhen Wang, Fan Bao, Chongxuan Li, Jun Zhu.* Preprint 2023.

- **[StyleDrop: Text-to-Image Generation in Any Style.](https://arxiv.org/abs/2306.00983)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Style-ff0000?style=flat-square)

    *Kihyuk Sohn, Nataniel Ruiz, Kimin Lee, Daniel Castro Chin, Irina Blok, Huiwen Chang, Jarred Barber, Lu Jiang, Glenn Entis, Yuanzhen Li, Yuan Hao, Irfan Essa, Michael Rubinstein, Dilip Krishnan.* NeurIPS'23. 🔥

    <img src="assets/styledrop.png" style="width:100%">

- **[Face0: Instantaneously Conditioning a Text-to-Image Model on a Face.](https://arxiv.org/abs/2306.06638)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Subject--Driven-orange?style=flat-square)

    *Dani Valevski, Danny Wasserman, Yossi Matias, Yaniv Leviathan.* SIGGRAPH Asia'23.

- **[Controlling Text-to-Image Diffusion by Orthogonal Finetuning.](https://arxiv.org/abs/2306.07280)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Layout-a50b5e?style=flat-square)![](https://img.shields.io/badge/Subject--Driven-orange?style=flat-square)

    *Zeju Qiu, Weiyang Liu, Haiwen Feng, Yuxuan Xue, Yao Feng, Zhen Liu, Dan Zhang, Adrian Weller, Bernhard Schölkopf.* NeruIPS'23.

- **[Zero-shot spatial layout conditioning for text-to-image diffusion models.](https://arxiv.org/abs/2306.13754)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Layout-a50b5e?style=flat-square)

    *Guillaume Couairon, Marlène Careil, Matthieu Cord, Stéphane Lathuilière, Jakob Verbeek.* ICCV'23.

- **[IP-Adapter: Text Compatible Image Prompt Adapter for Text-to-Image Diffusion Models.](https://arxiv.org/abs/2308.06721)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Subject--Driven-orange?style=flat-square)

    *Hu Ye, Jun Zhang, Sibo Liu, Xiao Han, Wei Yang.* Preprint 2023. 🔥

    <img src="assets/ip-adapter.png" style="width:100%">

- **[StyleAdapter: A Single-Pass LoRA-Free Model for Stylized Image Generation.](https://arxiv.org/abs/2309.01770)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Style-ff0000?style=flat-square)

    *Zhouxia Wang, Xintao Wang, Liangbin Xie, Zhongang Qi, Ying Shan, Wenping Wang, Ping Luo.* Preprint 2023.

- **[DreamStyler: Paint by Style Inversion with Text-to-Image Diffusion Models.](https://arxiv.org/abs/2309.06933)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Style-ff0000?style=flat-square)

    *Namhyuk Ahn, Junsoo Lee, Chunggi Lee, Kunhee Kim, Daesik Kim, Seung-Hun Nam, Kibeom Hong.* AAAI 2023.

- **[Kosmos-G: Generating Images in Context with Multimodal Large Language Models](https://arxiv.org/abs/2310.02992)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Subject--Driven-orange?style=flat-square)![](https://img.shields.io/badge/Compositionality-5218fa?style=flat-square)

    *Xichen Pan, Li Dong, Shaohan Huang, Zhiliang Peng, Wenhu Chen, Furu Wei.* Preprint 2023. 🔥

    <img src="assets/kosmos-g.png" style="width:100%">

- **[An Image is Worth Multiple Words: Learning Object Level Concepts using Multi-Concept Prompt Learning.](https://arxiv.org/abs/2310.12274)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Subject--Driven-orange?style=flat-square)

    *Chen Jin, Ryutaro Tanno, Amrutha Saseendran, Tom Diethe, Philip Teare.* Preprint 2023.

- **[CustomNet: Zero-shot Object Customization with Variable-Viewpoints in Text-to-Image Diffusion Models.](https://arxiv.org/abs/2310.19784)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/3D-3cb371?style=flat-square)![](https://img.shields.io/badge/Subject--Driven-orange?style=flat-square)

    *Ziyang Yuan, Mingdeng Cao, Xintao Wang, Zhongang Qi, Chun Yuan, Ying Shan.* Preprint 2023.

- **[Cross-Image Attention for Zero-Shot Appearance Transfer.](https://arxiv.org/abs/2311.03335)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Appearance-b78727?style=flat-square)

    *Yuval Alaluf, Daniel Garibi, Or Patashnik, Hadar Averbuch-Elor, Daniel Cohen-Or.* Preprint 2023.

- **[The Chosen One: Consistent Characters in Text-to-Image Diffusion Models.](https://arxiv.org/abs/2311.10093)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Consistency-ff69b4?style=flat-square)

    *Omri Avrahami, Amir Hertz, Yael Vinker, Moab Arar, Shlomi Fruchter, Ohad Fried, Daniel Cohen-Or, Dani Lischinski.* Preprint 2023.

- **[MagicDance: Realistic Human Dance Video Generation with Motions & Facial Expressions Transfer.](https://arxiv.org/abs/2311.12052)**

    ![](https://img.shields.io/badge/Video-9370db?style=flat-square)![](https://img.shields.io/badge/Layout-a50b5e?style=flat-square)

    *Di Chang, Yichun Shi, Quankai Gao, Jessica Fu, Hongyi Xu, Guoxian Song, Qing Yan, Xiao Yang, Mohammad Soleymani.* Preprint 2023.

- **[ZipLoRA: Any Subject in Any Style by Effectively Merging LoRAs.](https://arxiv.org/abs/2311.13600)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Subject--Driven-orange?style=flat-square)![](https://img.shields.io/badge/Style-ff0000?style=flat-square)

    *Viraj Shah, Nataniel Ruiz, Forrester Cole, Erika Lu, Svetlana Lazebnik, Yuanzhen Li, Varun Jampani.* Preprint 2023.

- **[StyleCrafter: Enhancing Stylized Text-to-Video Generation with Style Adapter.](https://arxiv.org/abs/2312.00330)**

    ![](https://img.shields.io/badge/Video-9370db?style=flat-square)![](https://img.shields.io/badge/Style-ff0000?style=flat-square)

    *Gongye Liu, Menghan Xia, Yong Zhang, Haoxin Chen, Jinbo Xing, Xintao Wang, Yujiu Yang, Ying Shan.* Preprint 2023.

- **[Style Aligned Image Generation via Shared Attention.](https://arxiv.org/abs/2312.02133)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Style-ff0000?style=flat-square)

    *Amir Hertz, Andrey Voynov, Shlomi Fruchter, Daniel Cohen-Or.* Preprint 2023. 🔥

    <img src="assets/style-aligned.png" style="width:100%">

- **[FaceStudio: Put Your Face Everywhere in Seconds.](https://arxiv.org/abs/2312.02663)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Subject--Driven-orange?style=flat-square)

    *Yuxuan Yan, Chi Zhang, Rui Wang, Yichao Zhou, Gege Zhang, Pei Cheng, Gang Yu, Bin Fu.* Preprint 2023.

- **[Context Diffusion: In-Context Aware Image Generation.](https://arxiv.org/abs/2312.03584)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Layout-a50b5e?style=flat-square)

    *Ivona Najdenkoska, Animesh Sinha, Abhimanyu Dubey, Dhruv Mahajan, Vignesh Ramanathan, Filip Radenovic.* Preprint 2023.

- **[PhotoMaker: Customizing Realistic Human Photos via Stacked ID Embedding.](https://arxiv.org/abs/2312.04461)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Subject--Driven-orange?style=flat-square)

    *Zhen Li, Mingdeng Cao, Xintao Wang, Zhongang Qi, Ming-Ming Cheng, Ying Shan.* Preprint 2023. 🔥

    <img src="assets/photomaker.png" style="width:100%">

- **[SCEdit: Efficient and Controllable Image Diffusion Generation via Skip Connection Editing.](arxiv.org/abs/2312.11392)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Layout-a50b5e?style=flat-square)

    *Zeyinzi Jiang, Chaojie Mao, Yulin Pan, Zhen Han, Jingfeng Zhang.* Preprint 2023.

- **[DreamTuner: Single Image is Enough for Subject-Driven Generation.](https://arxiv.org/abs/2312.13691)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Subject--Driven-orange?style=flat-square)

    *Miao Hua, Jiawei Liu, Fei Ding, Wei Liu, Jie Wu, Qian He.* Preprint 2023.

- **[PALP: Prompt Aligned Personalization of Text-to-Image Models.](https://arxiv.org/abs/2401.06105)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Subject--Driven-orange?style=flat-square)

    *Qixun Wang, Xu Bai, Haofan Wang, Zekui Qin, Anthony Chen.* Preprint 2024.

- **[InstantID: Zero-shot Identity-Preserving Generation in Seconds.](https://arxiv.org/abs/2401.07519)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Subject--Driven-orange?style=flat-square)

    *Qixun Wang, Xu Bai, Haofan Wang, Zekui Qin, Anthony Chen, Huaxia Li, Xu Tang, Yao Hu.* Preprint 2024. 🔥

    <img src="assets/instant-id.png" style="width:100%">

- **[Mastering Text-to-Image Diffusion: Recaptioning, Planning, and Generating with Multimodal LLMs.](https://arxiv.org/abs/2401.11708)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Layout-a50b5e?style=flat-square)

    *Ling Yang, Zhaochen Yu, Chenlin Meng, Minkai Xu, Stefano Ermon, Bin Cui.* Preprint 2024. 🔥

    <img src="assets/rpg.png" style="width:100%">

- **[UNIMO-G: Unified Image Generation through Multimodal Conditional Diffusion.](https://arxiv.org/abs/2401.13388)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Subject--Driven-orange?style=flat-square)![](https://img.shields.io/badge/Compositionality-5218fa?style=flat-square)

    *Wei Li, Xue Xu, Jiachen Liu, Xinyan Xiao.* Preprint 2024 🔥

    <img src="assets/unimo-g.png" style="width:100%">

- **[Object-Driven One-Shot Fine-tuning of Text-to-Image Diffusion with Prototypical Embedding](https://arxiv.org/abs/2401.15708)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Subject--Driven-orange?style=flat-square)

    *Jianxiang Lu, Cong Xie, Hui Guo.* Preprint 2024.

- **[Training-Free Consistent Text-to-Image Generation](https://arxiv.org/abs/2402.03286)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Consistency-ff69b4?style=flat-square)

    *Yoad Tewel, Omri Kaduri, Rinon Gal, Yoni Kasten, Lior Wolf, Gal Chechik, Yuval Atzmon.* Preprint 2024.

- **[InstanceDiffusion: Instance-level Control for Image Generation](https://arxiv.org/abs/2402.03290)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Layout-a50b5e?style=flat-square)

    *Xudong Wang, Trevor Darrell, Sai Saketh Rambhatla, Rohit Girdhar, Ishan Misra.* Preprint 2024.

- **[Text2Street: Controllable Text-to-image Generation for Street Views](https://arxiv.org/abs/2402.04504)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Layout-a50b5e?style=flat-square)

    *Jinming Su, Songen Gu, Yiting Duan, Xingyue Chen, Junfeng Luo.* Preprint 2024.

- **[λ-ECLIPSE: Multi-Concept Personalized Text-to-Image Diffusion Models by Leveraging CLIP Latent Space](https://arxiv.org/abs/2402.05195)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Subject--Driven-orange?style=flat-square)

    *Maitreya Patel, Sangmin Jung, Chitta Baral, Yezhou Yang.* Preprint 2024.

- **[ComFusion: Personalized Subject Generation in Multiple Specific Scenes From Single Image](https://arxiv.org/abs/2402.11849)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Subject--Driven-orange?style=flat-square)

    *Yan Hong, Jianfu Zhang.* Preprint 2024.

- **[Direct Consistency Optimization for Compositional Text-to-Image Personalization](https://arxiv.org/abs/2402.12004)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Subject--Driven-orange?style=flat-square)![](https://img.shields.io/badge/Compositionality-5218fa?style=flat-square)

    *Kyungmin Lee, Sangkyung Kwak, Kihyuk Sohn, Jinwoo Shin.* Preprint 2024. 🔥

    <img src="assets/dco.png" style="width:100%">

- **[MuLan: Multimodal-LLM Agent for Progressive Multi-Object Diffusion](https://arxiv.org/abs/2402.12741)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Compositionality-5218fa?style=flat-square)

    *Sen Li, Ruochen Wang, Cho-Jui Hsieh, Minhao Cheng, Tianyi Zhou.* Preprint 2024.

- **[RealCompo: Dynamic Equilibrium between Realism and Compositionality Improves Text-to-Image Diffusion Models](https://arxiv.org/abs/2402.12908)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Compositionality-5218fa?style=flat-square)

    *Xinchen Zhang, Ling Yang, Yaqi Cai, Zhaochen Yu, Jiake Xie, Ye Tian, Minkai Xu, Yong Tang, Yujiu Yang, Bin Cui.* Preprint 2024.

- **[Visual Style Prompting with Swapping Self-Attention](https://arxiv.org/abs/2402.12974)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Style-ff0000?style=flat-square)

    *Jaeseok Jeong, Junho Kim, Yunjey Choi, Gayoung Lee, Youngjung Uh.* Preprint 2024.

- **[Gen4Gen: Generative Data Pipeline for Generative Multi-Concept Composition](https://arxiv.org/abs/2402.15504)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Subject--Driven-orange?style=flat-square)![](https://img.shields.io/badge/Compositionality-5218fa?style=flat-square)

    *Chun-Hsiao Yeh, Ta-Ying Cheng, He-Yen Hsieh, Chuan-En Lin, Yi Ma, Andrew Markham, Niki Trigoni, H.T. Kung, Yubei Chen.* Preprint 2024.

- **[Multi-LoRA Composition for Image Generation](https://arxiv.org/abs/2402.16843)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Compositionality-5218fa?style=flat-square)

    *Ming Zhong, Yelong Shen, Shuohang Wang, Yadong Lu, Yizhu Jiao, Siru Ouyang, Donghan Yu, Jiawei Han, Weizhu Chen.* Preprint 2024.

- **[Continuous, Subject-Specific Attribute Control in T2I Models by Identifying Semantic Directions](https://arxiv.org/abs/2403.17064)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Subject--Driven-orange?style=flat-square)![](https://img.shields.io/badge/Appearance-b78727?style=flat-square)

    *Stefan Andreas Baumann, Felix Krause, Michael Neumayr, Nick Stracke, Vincent Tao Hu, Björn Ommer.* Preprint 2024.

- **[IDAdapter: Learning Mixed Features for Tuning-Free Personalization of Text-to-Image Models](https://arxiv.org/abs/2403.13535)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Subject--Driven-orange?style=flat-square)

    *Siying Cui, Jia Guo, Xiang An, Jiankang Deng, Yongle Zhao, Xinyu Wei, Ziyong Feng.* Preprint 2024. 🔥

    <img src="assets/id-adapter.png" style="width:100%">

- **[Be Yourself: Bounded Attention for Multi-Subject Text-to-Image Generation](https://arxiv.org/abs/2403.16990)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Compositionality-5218fa?style=flat-square)

    *Omer Dahary, Or Patashnik, Kfir Aberman, Daniel Cohen-Or.* Preprint 2024. 🔥

    <img src="assets/be-yourself.png" style="width:100%">

- **[FlashFace: Human Image Personalization with High-fidelity Identity Preservation](https://arxiv.org/abs/2403.17008)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Subject--Driven-orange?style=flat-square)

    *Shilong Zhang, Lianghua Huang, Xi Chen, Yifei Zhang, Zhi-Fan Wu, Yutong Feng, Wei Wang, Yujun Shen, Yu Liu, Ping Luo.* Preprint 2024. 🔥

    <img src="assets/flashface.png" style="width:100%">

- **[Concept Weaver: Enabling Multi-Concept Fusion in Text-to-Image Models](https://arxiv.org/abs/2404.03913)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Subject--Driven-orange?style=flat-square)![](https://img.shields.io/badge/Compositionality-5218fa?style=flat-square)

    *Gihyun Kwon, Simon Jenni, Dingzeyu Li, Joon-Young Lee, Jong Chul Ye, Fabian Caba Heilbron.* Preprint 2024.

- **[Identity Decoupling for Multi-Subject Personalization of Text-to-Image Models](https://arxiv.org/abs/2404.04243)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Subject--Driven-orange?style=flat-square)![](https://img.shields.io/badge/Compositionality-5218fa?style=flat-square)

    *Sangwon Jang, Jaehyeong Jo, Kimin Lee, Sung Ju Hwang.* Preprint 2024. 🔥

    <img src="assets/identity-decoupling.png" style="width:100%">

- **[MaxFusion: Plug&Play Multi-Modal Generation in Text-to-Image Diffusion Models](https://arxiv.org/abs/2404.09977)**

    ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Compositionality-5218fa?style=flat-square)

    *Nithin Gopalakrishnan Nair, Jeya Maria Jose Valanarasu, Vishal M Patel.* Preprint 2024.



### Consistency Models



- **[CCM: Adding Conditional Controls to Text-to-Image Consistency Models](https://arxiv.org/abs/2312.06971)** ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Layout-a50b5e?style=flat-square)

    *Jie Xiao, Kai Zhu, Han Zhang, Zhiheng Liu, Yujun Shen, Yu Liu, Xueyang Fu, Zheng-Jun Zha.* Preprint 2023.

- **[PIXART-δ: Fast and Controllable Image Generation with Latent Consistency Models](https://arxiv.org/abs/2401.05252)** ![](https://img.shields.io/badge/Image-blue?style=flat-square)![](https://img.shields.io/badge/Layout-a50b5e?style=flat-square)

    *Junsong Chen, Yue Wu, Simian Luo, Enze Xie, Sayak Paul, Ping Luo, Hang Zhao, Zhenguo Li.* Preprint 2024.



 ## Other Resources

 

- **[Regional Prompter](https://github.com/hako-mikan/sd-webui-regional-prompter)**  Set a prompt to a divided region.


 
 ## Other Awesome Lists



- **[Awesome-LLM-Reasoning](https://github.com/atfortes/Awesome-LLM-Reasoning)**  Collection of papers and resources on Reasoning in Large Language Models.



## Contributing



- Add a new paper or update an existing paper, thinking about which category the work should belong to.
- Use the same format as existing entries to describe the work.
- Add the abstract link of the paper (`/abs/` format if it is an arXiv publication).

**Don't worry if you do something wrong, it will be fixed for you!**

### Contributors

<a href="https://github.com/atfortes/Awesome-Controllable-Generation/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=atfortes/Awesome-Controllable-Generation" />
</a>
