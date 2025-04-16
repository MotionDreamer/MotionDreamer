# MotionDreamer: MotionDreamer: One-to-Many Motion Synthesis with Localized Generative Masked Transformer


 <p align="center">
    <a href="https://arxiv.org/abs/2504.08959"><img alt="arXiv" src="https://img.shields.io/badge/arXiv-2504.08959-b31b1b.svg"></a>
    <a href="https://motiondreamer.github.io"><img alt="Project Page" src="https://img.shields.io/badge/-Project%20Page-lightgrey?logo=Google%20Chrome&color=informational&logoColor=white"></a>
    
</p>

![teaser_image](assets/overview.png)
If you find our code or paper helpful, please consider starring our repository and citing:
```
@inproceedings{wang2025motiondreamer,
    title={MotionDreamer: One-to-Many Motion Synthesis with Localized Generative Masked Transformer},
    author={Yilin Wang and chuan guo and Yuxuan Mu and Muhammad Gohar Javed and Xinxin Zuo and Juwei Lu and Hai Jiang and Li cheng},
    booktitle={The Thirteenth International Conference on Learning Representations},
    year={2025},
    url={https://openreview.net/forum?id=d23EVDRJ6g}
}

```
[Project Page](https://motiondreamer.github.io)

Generative masked transformer have demonstrated remarkable success across various content generation tasks, primarily due to their ability to effectively model large-scale dataset distributions with high consistency. However, in the animation domain, large datasets are not always available. Applying generative masked modeling to generate diverse instances from a single MoCap reference may lead to overfitting, a challenge that remains unexplored. In this work, we present MotionDreamer, a localized masked modeling paradigm designed to learn motion internal patterns from a given motion with arbitrary topology and duration. By embedding the given motion into quantized tokens with a novel distribution regularization method, MotionDreamer constructs a robust and informative codebook for local motion patterns. Moreover, a sliding window local attention is introduced in our masked transformer, enabling the generation of natural yet diverse animations that closely resemble the reference motion patterns. As demonstrated through comprehensive experiments, MotionDreamer outperforms the state-of-the-art methods that are typically GAN or Diffusion-based in both faithfulness and diversity. Thanks to the consistency and robustness of quantization-based approach, MotionDreamer can also effectively perform downstream tasks such as temporal motion editing, crowd motion synthesis, and beat-aligned dance generation, all using a single reference motion.

<!--
**MotionDreamer/MotionDreamer** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
