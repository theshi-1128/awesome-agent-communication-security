<h1 align="center">🚀 Awesome Agent Communication Security</h1>

<p align="center"><b>
A curated collection of research and techniques on securing agent communication in Large Language Model (LLM)–based agent systems, including protocols, security risks, defense countermeasures, and more.
</b></p>

<p align="center">
  <a href="https://github.com/theshi-1128/awesome-agent-communication-security">
    <img src="https://awesome.re/badge.svg" alt="Awesome"/>
  </a>
  <img src="https://img.shields.io/github/last-commit/theshi-1128/awesome-agent-communication-security?color=green" alt="Last Commit"/>
  <img src="https://img.shields.io/badge/PRs-Welcome-red" alt="PRs Welcome"/>
  <img src="https://img.shields.io/github/stars/theshi-1128/awesome-agent-communication-security?color=yellow" alt="Stars"/>
  <img src="https://img.shields.io/github/forks/theshi-1128/awesome-agent-communication-security?color=lightblue" alt="Forks"/>
</p>

<hr/>

<h2>📝 Abstract</h2>

<p align="justify">
In recent years, Large-Language-Model-driven AI agents have exhibited unprecedented intelligence and adaptability. Nowadays, agents are undergoing a new round of evolution. They no longer act as an isolated island like LLMs. Instead, they start to communicate with diverse external entities, such as other agents and tools, to perform more complex tasks collectively. Under this trend, agent communication is regarded as a foundational pillar of the future AI ecosystem, and many organizations have intensively begun to design related communication protocols (e.g., Anthropic's MCP and Google's A2A) within the past year. However, this new field exposes significant security hazards, which can cause severe damage to real-world scenarios. 
</p>

<p align="justify">
To help researchers quickly figure out this promising topic and benefit the future agent communication development, this paper presents a comprehensive survey of agent communication security. 
  - More precisely, we present the first clear definition of agent communication. 
  
  - Besides, we propose a framework that categorizes agent communication into three classes and uses a three-layered communication architecture to illustrate how each class works.
  - 
  - Next, for each communication class, we dissect related communication protocols and analyze the security risks, illustrating which communication layer the risks arise from.
  - 
  - Then, we provide an outlook on the possible defense countermeasures for each risk.
  - 
  - In addition, we conduct experiments using MCP and A2A to help readers better understand the novel vulnerabilities brought by agent communication.
  - 
  - Finally, we discuss open issues and future directions in this promising research field. 
</p>


<p align="justify">
We will continue to maintain and update this curated list of related papers and resources in this repository.
</p>

<p align="center">
  <img src="agentcommunication.png" width="1200"/>
</p>

<hr/>

## Collections
- [Book](collection/book.md) (3)
- [Competition](collection/competition.md) (5)
- [Leaderboard](collection/leaderboard.md) (3)
- [Toolkit](collection/toolkit.md) (10)
- [Survey](collection/survey.md) (35)
- Paper (1467)
    - A. Safety (806)
        - [A0. General](collection/paper/safety/general.md) (22)
        - [A1. Jailbreak](collection/paper/safety/jailbreak.md) (340)
        - [A2. Alignment](collection/paper/safety/alignment.md) (89)
        - [A3. Deepfake](collection/paper/safety/deepfake.md) (64)
        - [A4. Ethics](collection/paper/safety/ethics.md) (5)
        - [A5. Fairness](collection/paper/safety/fairness.md) (54)
        - [A6. Hallucination](collection/paper/safety/hallucination.md) (109)
        - [A7. Prompt Injection](collection/paper/safety/prompt_injection.md) (49)
        - [A8. Toxicity](collection/paper/safety/toxicity.md) (74)
    - B. Security (220)
        - [B0. General](collection/paper/security/general.md) (13)
        - [B1. Adversarial Examples](collection/paper/security/adversarial_examples.md) (89)
        - [B2. Poison & Backdoor](collection/paper/security/poison_&_backdoor.md) (105)
        - [B3. System](collection/paper/security/system.md) (13)
    - C. Privacy (441)
        - [C0. General](collection/paper/privacy/general.md) (31)
        - [C1. Contamination](collection/paper/privacy/contamination.md) (13)
        - [C2. Copyright](collection/paper/privacy/copyright.md) (156)
        - [C3. Data Reconstruction](collection/paper/privacy/data_reconstruction.md) (48)
        - [C4. Membership Inference Attacks](collection/paper/privacy/membership_inference_attacks.md) (39)
        - [C5. Model Extraction](collection/paper/privacy/model_extraction.md) (12)
        - [C6. Privacy-Preserving Computation](collection/paper/privacy/privacy-preserving_computation.md) (88)
        - [C7. Property Inference Attacks](collection/paper/privacy/property_inference_attacks.md) (3)
        - [C8. Side-Channel](collection/paper/privacy/side-channel.md) (5)
        - [C9. Unlearning](collection/paper/privacy/unlearning.md) (46)
<hr/>

<h2>🌟 Features</h2>

<ul>
  <li><b>Comprehensive Survey:</b> Presents the first systematic and theoretically grounded survey of agent communication security, spanning communication architectures, protocol designs, risk taxonomies, and defense methodologies.</li>
  <li><b>Systematic Categorization:</b> Formalizes a unified classification of agent communication modes and proposes a three-layered communication framework that rigorously maps communication processes to their corresponding security risks.</li>
  <li><b>Actively Updated:</b> Tracks the latest protocols, security analyses, and defense techniques, supporting reproducible research and fostering future studies in secure agent communication.</li>
  <li><b>Open Source & Community Driven:</b> Contributions and suggestions are welcome!</li>
</ul>




<hr/>

<h2>🤝 Contributing</h2>
<p>
We welcome contributions! Feel free to <a href="https://github.com/theshi-1128/awesome-agent-communication-security/issues">open an issue</a> or submit a pull request.
</p>

<hr/>


<h2>📖 Citation</h2>

<p>If you find this work useful in your own research, please feel free to leave a star⭐️ and cite our paper:

```bibtex
@article{kong2025survey,
  title={A survey of llm-driven ai agent communication: Protocols, security risks, and defense countermeasures},
  author={Kong, Dezhang and Lin, Shi and Xu, Zhenhua and Wang, Zhebo and Li, Minghao and Li, Yufeng and Zhang, Yilun and Peng, Hujin and Sha, Zeyang and Li, Yuyuan and others},
  journal={arXiv preprint arXiv:2506.19676},
  year={2025}
}
```

<hr/>

<p align="center" style="font-size:1.1rem;">
  <b>For questions or suggestions:</b> <a href="mailto:linshizjsu@gmail.com">linshizjsu@gmail.com</a>, </b> <a href="mailto:kdz@zju.edu.cn">kdz@zju.edu.cn</a>
</p>
