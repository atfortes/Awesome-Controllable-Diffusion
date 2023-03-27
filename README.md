<h1 align="center">Multimodal Reasoning</h1>

<p align="center">
    <img src="https://awesome.re/badge.svg" href="https://github.com/atfortes/Multimodal-Reasoning-Papers"/>
    <img src="https://img.shields.io/badge/License-MIT-green.svg" href="https://opensource.org/licenses/MIT"/>
    <img src="https://img.shields.io/badge/PRs-Welcome-red"/>
    <img src="https://img.shields.io/github/last-commit/atfortes/Multimodal-Reasoning-Papers?color=green"/>
</p>

<p align="center">
    <b> Collection of papers and resources on how to unlock reasoning abilities under multimodal settings.</b>
</p>

<p align="center">
    <img src="https://github.com/cvlab-columbia/viper/blob/main/teaser.gif" width="100%" style="align:center;"/>
</p>

<p align="right">
    <i>Animation from <a href="https://viper.cs.columbia.edu/">ViperGPT (Surís et al.)</a></i>
</p>

<p align="center">
    Consider how difficult it would be to study from a book that lacks any figures, diagrams or tables. We enhance our learning ability when we combine different data modalities, such as vision, language, and audio. Recently, large language models (LLMs) have achieved remarkable results in complex reasoning tasks by generating intermediate steps before deducing the answer via chain-of-thought (CoT) reasoning. However, most of the research on CoT reasoning only involves the language modality and not others. We present a collection of papers and resources on how to unlock these abilities under multimodal settings.
</p>



## Contents



 - [Technique](#technique)
    - [End-to-end Models](#e2e)
    - [Prompting & In-context Learning](#prompt)
    - [Symbolic Approach](#symbolic)
 - [Benchmark](#benchmark)
 - [Other Awesome Lists](#other-awesome-lists)
 - [Contributing](#contributing)
 
 
 
 ## Technique
 
 <h3 id="e2e">End-to-end Models</h3>
 
 

1. **Flamingo: a Visual Language Model for Few-Shot Learning.** `NeurIPS 2022`

    *Jean-Baptiste Alayrac, Jeff Donahue, Pauline Luc, Antoine Miech, Iain Barr, Yana Hasson, Karel Lenc, Arthur Mensch, Katie Millican, Malcolm Reynolds, Roman Ring, Eliza Rutherford, Serkan Cabi, Tengda Han, Zhitao Gong, Sina Samangooei, Marianne Monteiro, Jacob Menick, Sebastian Borgeaud, Andrew Brock, Aida Nematzadeh, Sahand Sharifzadeh, Mikolaj Binkowski, Ricardo Barreira, Oriol Vinyals, Andrew Zisserman, Karen Simonyan.* [[Blog](https://www.deepmind.com/blog/tackling-multiple-tasks-with-a-single-visual-language-model)] [[Paper](https://arxiv.org/abs/2204.14198)], 2022.4

1. **BLIP-2: Bootstrapping Language-Image Pre-training with Frozen Image Encoders and Large Language Models.** `Preprint`

    *Junnan Li, Dongxu Li, Silvio Savarese, Steven Hoi.* [[Paper](https://arxiv.org/abs/2301.12597)] [[Code](https://github.com/salesforce/LAVIS/tree/main/projects/blip2)], 2023.1

1. **Language Is Not All You Need: Aligning Perception with Language Models.** `Preprint`

    *Shaohan Huang, Li Dong, Wenhui Wang, Yaru Hao, Saksham Singhal, Shuming Ma, Tengchao Lv, Lei Cui, Owais Khan Mohammed, Barun Patra, Qiang Liu, Kriti Aggarwal, Zewen Chi, Johan Bjorck, Vishrav Chaudhary, Subhojit Som, Xia Song, Furu Wei.* [[Paper](https://arxiv.org/abs/2302.14045)], 2023.2

1. **Prismer: A Vision-Language Model with An Ensemble of Experts.** `Preprint`

    *Shikun Liu, Linxi Fan, Edward Johns, Zhiding Yu, Chaowei Xiao, Anima Anandkumar.* [[Project](https://shikun.io/projects/prismer)] [[Paper](https://arxiv.org/abs/2303.02506)] [[Code](https://github.com/NVlabs/prismer)] [[Demo](https://huggingface.co/spaces/lorenmt/prismer)], 2023.3

1. **PaLM-E: An Embodied Multimodal Language Model.** `Preprint`

    *Danny Driess, Fei Xia, Mehdi S. M. Sajjadi, Corey Lynch, Aakanksha Chowdhery, Brian Ichter, Ayzaan Wahid, Jonathan Tompson, Quan Vuong, Tianhe Yu, Wenlong Huang, Yevgen Chebotar, Pierre Sermanet, Daniel Duckworth, Sergey Levine, Vincent Vanhoucke, Karol Hausman, Marc Toussaint, Klaus Greff, Andy Zeng, Igor Mordatch, Pete Florence.* [[Project](https://palm-e.github.io/)] [[Paper](https://arxiv.org/abs/2303.03378)], 2023.3

1. **GPT-4 Technical Report.** `Preprint`

    *OpenAI.* [[Blog](https://openai.com/research/gpt-4)] [[Paper](https://arxiv.org/abs/2303.08774)], 2023.3



<h3 id="prompt">Prompting & In-context Learning</h3>



1. **Multimodal Chain-of-Thought Reasoning in Language Models.** `Preprint`

    *Zhuosheng Zhang, Aston Zhang, Mu Li, Hai Zhao, George Karypis, Alex Smola.* [[Paper](https://arxiv.org/abs/2302.00923)] [[Code](https://github.com/amazon-science/mm-cot)], 2023.2

1. **Visual ChatGPT: Talking, Drawing and Editing with Visual Foundation Models.** `Preprint`

    *Chenfei Wu, Shengming Yin, Weizhen Qi, Xiaodong Wang, Zecheng Tang, Nan Duan.* [[Paper](https://arxiv.org/abs/2303.04671)] [[Code](https://github.com/microsoft/visual-chatgpt)], 2023.3

1. **MM-REACT: Prompting ChatGPT for Multimodal Reasoning and Action.** `Preprint`

    *Zhengyuan Yang, Linjie Li, Jianfeng Wang, Kevin Lin, Ehsan Azarnasab, Faisal Ahmed, Zicheng Liu, Ce Liu, Michael Zeng, Lijuan Wang.* [[Project](https://multimodal-react.github.io/)] [[Paper](https://arxiv.org/abs/2303.11381)] [[Code](https://github.com/microsoft/MM-REACT)] [[Demo](https://huggingface.co/spaces/microsoft-cognitive-service/mm-react)], 2023.3



<h3 id="symbolic">Symbolic Approach</h3>



1. **Visual Programming: Compositional visual reasoning without training.** `CPVR 2023`

    *Tanmay Gupta, Aniruddha Kembhavi.* [[Project](https://prior.allenai.org/projects/visprog)] [[Paper](https://arxiv.org/abs/2211.11559)], 2022.11


1. **ViperGPT: Visual Inference via Python Execution for Reasoning.** `Preprint`

    *Dídac Surís, Sachit Menon, Carl Vondrick.* [[Project](https://viper.cs.columbia.edu/)] [[Paper](https://arxiv.org/abs/2303.08128)] [[Code](https://github.com/cvlab-columbia/viper)], 2023.3



 ## Benchmark



- **[SCIENCEQA](https://arxiv.org/abs/2209.09513)**  Multimodal multiple choice questions with diverse science topics and annotations of their answers with corresponding lectures and explanations.
- **[OK-VQA](https://arxiv.org/abs/1906.00067)**  Visual question answering that requires methods which can draw upon outside knowledge to answer questions.
- **[A-OKVQA](https://arxiv.org/abs/2206.01718)**  Knowledge-based visual question answering benchmark.
- **[NExT-QA](https://arxiv.org/abs/2105.08276)**  Video question answering (VideoQA) benchmark to advance video understanding from describing to explaining the temporal actions.
- **[GQA](https://arxiv.org/abs/1902.09506)**  Compositional questions over real-world images.
- **[VQA](https://arxiv.org/abs/1505.00468)**  Questions about images that require an understanding of vision, language and commonsense knowledge.
- **[VQAv2](https://arxiv.org/abs/1612.00837)**  The 2nd iteration of the Visual Question Answering Dataset (VQA).
- **[ARC](https://arxiv.org/abs/1911.01547)**  General artificial intelligence benchmark, targetted at artificially intelligent systems that aim at emulating a human-like form of general fluid intelligence.


  
 ## Other Awesome Lists



- **[LLM-Reasoning-Papers](https://github.com/atfortes/LLM-Reasoning-Papers)**  Collection of papers and resources on Reasoning in Large Language Models, including Chain-of-Thought, Instruction-Tuning, and others.
- **[Chain-of-ThoughtsPapers](https://github.com/Timothyxxx/Chain-of-ThoughtsPapers)**  A trend starts from "Chain-of-Thought Prompting Elicits Reasoning in Large Language Models".
- **[Prompt4ReasoningPapers](https://github.com/zjunlp/Prompt4ReasoningPapers)**  Repository for the paper "Reasoning with Language Model Prompting: A Survey".
- **[Deep-Reasoning-Papers](https://github.com/floodsung/Deep-Reasoning-Papers)**  Recent Papers including Neural Symbolic Reasoning, Logical Reasoning, Visual Reasoning, planning and any other topics connecting deep learning and reasoning.



## Contributing



- Add a new paper or update an existing paper, thinking about which category the work should belong to.
- Use the same format as existing entries to describe the work.
- Add the abstract link of the paper (`/abs/` format if it is an arXiv publication).

**Don't worry if you do something wrong, it will be fixed for you!**

### Contributors

<a href="https://github.com/atfortes/Multimodal-Reasoning-Papers/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=atfortes/Multimodal-Reasoning-Papers" />
</a>
