<h1 align="center">🚀 Awesome Agent Communication Security</h1>

<p align="center"><b>
A curated collection of research and techniques on securing agent communication in Large Language Model (LLM)–based agent systems, including protocols, security risks, defense countermeasures, and more.
</b></p>


<p align="center">
  <a href="https://github.com/theshi-1128/awesome-agent-communication-security">
    <img src="https://awesome.re/badge.svg" alt="Awesome"/>
  </a>
  <a href="https://arxiv.org/abs/2506.19676">
    <img src="https://img.shields.io/badge/arXiv-paper-red.svg" alt="arXiv: paper"/>
  </a>
  <img src="https://img.shields.io/github/last-commit/theshi-1128/awesome-agent-communication-security?color=green" alt="Last Commit"/>
  <img src="https://img.shields.io/badge/PRs-Welcome-red" alt="PRs Welcome"/>
  <img src="https://img.shields.io/github/stars/theshi-1128/awesome-agent-communication-security?color=yellow" alt="Stars"/>
  <img src="https://img.shields.io/github/forks/theshi-1128/awesome-agent-communication-security?color=lightblue" alt="Forks"/>
</p>

<hr/>

<h2>📝 Abstract</h2>

<p align="justify">
In recent years, LLM-driven AI agents have exhibited unprecedented intelligence and adaptability. Nowadays, agents are undergoing a new round of evolution. They no longer act as an isolated island like LLMs. Instead, they start to communicate with diverse external entities, such as other agents and tools, to perform more complex tasks collectively. Under this trend, agent communication is regarded as a foundational pillar of the future AI ecosystem, and many organizations have intensively begun to design related communication protocols (e.g., Anthropic's MCP and Google's A2A) within the past year. However, this new field exposes significant security hazards, which can cause severe damage to real-world scenarios. 
</p>

<p align="justify">

To help researchers rapidly grasp this emerging yet critical topic and advance future agent communication development, this paper presents a comprehensive survey of agent communication security:

- 🧭 **New Conceptualization:** We provide the first precise and unified definition of LLM-driven agent communication.

- 🏗️ **Novel Systematic Taxonomy:** We introduce **a novel 3*3 framework** that classifies agent communication into three categories and describe a three-layer communication architecture to explain how each category operates.

    - 🏗️ **Protocols Classification:** Based on this 3*3 framework, we dissect representative communication protocols and classify them according to their features.

    - ⚠️ **Risk Analysis/Prospect:** Based on this 3*3 framework, we analyze the associated security risks, indicating which communication layer each risk originates from. We not only collect the published ones but also analyze **the potential risks that have not been studied.**

    - 🛡️ **Defensive Outlook:** For each risk, We not only summarize the published defenses but also propose **the potential countermeasures that have not been studied in time.**

- 🔍 **Empirical Demonstration:** We conduct experiments on **MCP** and **A2A** to reveal novel vulnerabilities arising in real agent communication systems.

- 🚀 **Future Directions:** Finally, we outline open challenges and promising research opportunities in this rapidly evolving field.

-  **Continuous Update:** We will continue to maintain and update this curated list of related papers and resources in this repository.

</p>



<p align="center">
  <img src="agentcommunication.png" width="1200"/>
</p>

<hr/>


## 🧩 Related Work Matrix
**Note**: Due to the forward-looking nature of this paper, the risks and defenses we mentioned include both **the proposed ones** and **potential directions that have not been studied**. As a result, some risks/defense may lack a concrete list of papers, we hope our paper can inspire these directions.


<table>
  <thead>
    <tr>
      <th style="text-align:center;">
        Layers ↓ / Classes → 
      </th>
      <th style="text-align:center;">User ↔ Agent</th>
      <th style="text-align:center;">Agent ↔ Agent</th>
      <th style="text-align:center;">Agent ↔ Environment</th>
    </tr>
  </thead>

  <tbody>

<!-- L1 -->
<tr>
  <th style="text-align:center;">🔵 L1 — Data Transmission Layer</th>
  <td width="25%">
    <div><b>⚠️ </b> <a href="collection/paper&report/user-agent-interaction/risks/risks-from-L1.md">Risks (attacks)</a></div>
    <div><b>🛡️ </b> <a href="collection/paper&report/user-agent-interaction/defenses/defenses-on-L1.md">Defenses</a></div>
  </td>
  <td width="25%">
    <div><b>⚠️ </b> <a href="collection/paper&report/agent-agent-communication/risks/risks-from-L1.md">Risks (attacks)</a></div>
    <div><b>🛡️ </b> <a href="collection/paper&report/agent-agent-communication/defenses/defenses-on-L1.md">Defenses</a></div>
  </td>
  <td width="25%">
    <div><b>⚠️ </b> <a href="collection/paper&report/agent-environment-communication/risks/risks-from-L1.md">Risks (attacks)</a></div>
    <div><b>🛡️ </b> <a href="collection/paper&report/agent-environment-communication/defenses/defenses-on-L1.md">Defenses</a></div>
  </td>
</tr>

<!-- L2 -->
<tr>
  <th style="text-align:center;">🟣 L2 — Interaction Protocol Layer</th>
  <td>
    <div><b>📡 </b><a href="collection/paper&report/user-agent-interaction/protocols/user-agent-interaction-protocols.md">Protocols</a></div>
    <div><b>⚠️ </b> <a href="collection/paper&report/user-agent-interaction/risks/risks-from-L2.md">Risks (attacks)</a></div>
    <div><b>🛡️ </b> <a href="collection/paper&report/user-agent-interaction/defenses/defenses-on-L2.md">Defenses</a></div>
  </td>

  <td>
    <div><b>📡 </b>
      <a href="collection/paper&report/agent-agent-communication/protocols/">Protocols</a>,
    </div>
    <div><b>⚠️ </b> <a href="collection/paper&report/agent-agent-communication/risks/risks-from-L2.md">Risks (attacks)</a></div>
    <div><b>🛡️ </b> <a href="collection/paper&report/agent-agent-communication/defenses/defenses-on-L2.md">Defenses</a></div>
  </td>

  <td>
    <div><b>📡 </b><a href="collection/paper&report/agent-environment-communication/protocols/agent-environment-communication-protocols.md">Protocols</a></div>
    <div><b>⚠️ </b> <a href="collection/paper&report/agent-environment-communication/risks/risks-from-L2.md">Risks (attacks)</a></div>
    <div><b>🛡️ </b> <a href="collection/paper&report/agent-environment-communication/defenses/defenses-on-L2.md">Defenses</a></div>
  </td>
</tr>

<!-- L3 -->
<tr>
  <th style="text-align:center;">🔶 L3 — Semantic Interpretation Layer</th>
  <td>
    <div><b>⚠️ </b> <a href="collection/paper&report/user-agent-interaction/risks/risks-from-L3.md">Risks (attacks)</a></div>
    <div><b>🛡️ </b> <a href="collection/paper&report/user-agent-interaction/defenses/defenses-on-L3.md">Defenses</a></div>
  </td>
  <td>
    <div><b>⚠️ </b> <a href="collection/paper&report/agent-agent-communication/risks/risks-from-L3.md">Risks (attacks)</a></div>
    <div><b>🛡️ </b> <a href="collection/paper&report/agent-agent-communication/defenses/defenses-on-L3.md">Defenses</a></div>
  </td>
  <td>
    <div><b>⚠️ </b> <a href="collection/paper&report/agent-environment-communication/risks/risks-from-L3.md">Risks (attacks)</a></div>
    <div><b>🛡️ </b> <a href="collection/paper&report/agent-environment-communication/defenses/defenses-on-L3.md">Defenses</a></div>
  </td>
</tr>

  </tbody>
</table>


<hr/>

<h2>🌟 Features</h2>

<ul>
  <li><b>Comprehensive Survey:</b> Presents the first systematic and theoretically grounded survey of agent communication security, spanning communication architectures, protocol designs, risk taxonomies, and defense methodologies.</li>
  <li><b>Systematic Categorization:</b> Formalizes a unified classification of agent communication modes and proposes a three-layered communication framework that rigorously maps communication processes to their corresponding security risks.</li>
  <li><b>Actively Updated:</b> Tracks the latest protocols, security analyses, and defense techniques, supporting reproducible research and fostering future studies in secure agent communication.</li>
  <li><b>Open Source & Community Driven:</b> Contributions and suggestions are welcome!</li>
</ul>



<hr/>





<h2>🤝 Submitting Your Papers</h2>

Agent communication security is a hot, rapidly evolving field. As a result, if your paper is relevant but not included, please feel free to <a href="https://github.com/theshi-1128/awesome-agent-communication-security/issues">open an issue</a> or submit a pull request. <b>Since our paper is garnering citations rapidly, <span style="color:red">submitting your paper will help your work gain higher exposure.</span> </b>


 
Please tell us the following characteristics of your papers:
- agent communication class: protocols/attacks/defense.
- communication layer: L1/L2/L3.

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
