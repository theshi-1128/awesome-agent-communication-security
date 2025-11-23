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
To help researchers quickly figure out this promising topic and benefit the future agent communication development, this paper presents a comprehensive survey of agent communication security. More precisely, we present the first clear definition of agent communication. Besides, we propose a framework that categorizes agent communication into three classes and uses a three-layered communication architecture to illustrate how each class works. Next, for each communication class, we dissect related communication protocols and analyze the security risks, illustrating which communication layer the risks arise from. Then, we provide an outlook on the possible defense countermeasures for each risk. In addition, we conduct experiments using MCP and A2A to help readers better understand the novel vulnerabilities brought by agent communication. Finally, we discuss open issues and future directions in this promising research field. 
</p>


<p align="justify">
We will continue to maintain and update this curated list of related papers and resources in this repository.
</p>

<hr/>

<h2>📖 Documentation</h2>

<div align="center">
  <table>
    <tr>
      <td align="center" width="50%">
        <h3>📄 Survey Paper</h3>
        <p><b><a href="https://arxiv.org/abs/2508.11548" target="_blank">Copyright Protection for Large Language Models: A Survey of Methods, Challenges, and Trends</a></b></p>
        <p><code>arXiv:2508.11548</code></p>
        <p><i>Comprehensive academic survey covering LLM copyright protection techniques</i></p>
      </td>
      <td align="center" width="50%">
        <h3>🌐 Interactive Website</h3>
        <p><b><a href="https://xuzhenhua55.github.io/awesome-llm-copyright-protection/" target="_blank">View Full Documentation & Papers</a></b></p>
        <p><code>GitHub Pages</code></p>
        <p><i>Interactive platform with organized papers, code links, and resources</i></p>
      </td>
    </tr>
  </table>
</div>

<p align="justify">
This project is a website version of our arXiv paper <a href="https://arxiv.org/abs/2508.11548" target="_blank">"Copyright Protection for Large Language Models: A Survey of Methods, Challenges, and Trends"</a>, aiming to provide a more interactive and accessible platform for researchers and practitioners in the field of LLM copyright protection. We begin with a comprehensive preliminary section that introduces essential background knowledge for understanding various LLM IP protection methods. We provide updated definitions of key concepts such as model watermarking and model fingerprinting in the context of 2025, enabling newcomers to clearly distinguish between these often-confused concepts.
</p>

<p align="justify">
Our ultimate goal is to present a comprehensive pipeline of copyright protection methods for large language models. From contemporary model fingerprint definitions to fingerprint embedding (and extraction) techniques, and from fingerprint transfer to removal strategies, we provide an end-to-end overview of the entire process.
</p>

<p align="justify">
🌟 This website serves as a valuable resource for researchers and practitioners, providing quick access to paper references, code links, and future resources for paper interpretation and analysis.
</p>

<hr/>

<h2>🗂️ Project Structure</h2>

<div align="center">
  <table>
    <tr>
      <td width="100%">
        <pre>
📚 <b>Preliminary</b>
   └─ Background Knowledge & Definitions

🔍 <b>Model Fingerprinting</b>
   ├─ <b>Non-invasive Fingerprinting</b>
   │    ├─ Parameter and Representation Based
   │    │    ├─ Parameter Space
   │    │    └─ Representation Features
   │    ├─ Semantic Feature Extraction
   │    └─ Adversarial Example-Based
   │
   └─ <b>Invasive Fingerprinting</b>
        ├─ Weight Watermark as Fingerprint
        └─ Backdoor Watermark as Fingerprint

🔄 <b>Fingerprint Transfer</b>
   └─ Cross-model Fingerprint Migration

🧹 <b>Fingerprint Removal</b>
   └─ Detection & Elimination Techniques
        </pre>
      </td>
    </tr>
  </table>
</div>

<hr/>

<h2>🌟 Features</h2>

<ul>
  <li><b>Comprehensive Survey:</b> Covers both classic and cutting-edge LLM copyright protection techniques.</li>
  <li><b>Systematic Categorization:</b> Clear taxonomy of fingerprinting and watermarking methods.</li>
  <li><b>Open Source & Community Driven:</b> Contributions and suggestions are welcome!</li>
</ul>

<hr/>

<h2>🤝 Contributing</h2>
<p>
We welcome contributions! Feel free to <a href="https://github.com/Xuzhenhua55/awesome-llm-copyright-protection/issues">open an issue</a> or submit a pull request.
</p>

<hr/>


<h2>📖 Citation</h2>

<p>If you find our survey useful for your research, please consider citing:</p>

<details>
<summary><b>BibTeX</b></summary>

```bibtex
@misc{xu2025copyrightprotectionlargelanguage,
      title={Copyright Protection for Large Language Models: A Survey of Methods, Challenges, and Trends}, 
      author={Zhenhua Xu and Xubin Yue and Zhebo Wang and Qichen Liu and Xixiang Zhao and Jingxuan Zhang and Wenjun Zeng and Wengpeng Xing and Dezhang Kong and Changting Lin and Meng Han},
      year={2025},
      eprint={2508.11548},
      archivePrefix={arXiv},
      primaryClass={cs.CR},
      url={https://arxiv.org/abs/2508.11548}, 
}
```

</details>

<hr/>

<p align="center" style="font-size:1.1rem;">
  ⭐️ If you find this project helpful, please consider <a href="https://github.com/Xuzhenhua55/awesome-llm-copyright-protection" target="_blank"><b>starring us on GitHub</b></a>!<br>
  <b>For questions or suggestions:</b> <a href="mailto:xuzhenhua0326@zju.edu.cn">xuzhenhua0326@zju.edu.cn</a>
</p>
