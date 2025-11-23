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
In recent years, LLM-driven AI agents have exhibited unprecedented intelligence and adaptability. Nowadays, agents are undergoing a new round of evolution. They no longer act as an isolated island like LLMs. Instead, they start to communicate with diverse external entities, such as other agents and tools, to perform more complex tasks collectively. Under this trend, agent communication is regarded as a foundational pillar of the future AI ecosystem, and many organizations have intensively begun to design related communication protocols (e.g., Anthropic's MCP and Google's A2A) within the past year. However, this new field exposes significant security hazards, which can cause severe damage to real-world scenarios. 
</p>

<p align="justify">

To help researchers rapidly grasp this emerging yet critical topic and advance future agent communication development, this paper presents a comprehensive survey of agent communication security:

- 🧭 **Clear Conceptualization:** We provide the first precise and unified definition of agent communication.

- 🏗️ **Systematic Taxonomy:** We introduce a framework that classifies agent communication into three categories and describe a three-layer communication architecture to explain how each category operates.

- ⚠️ **Risk Analysis:** For each communication class, we dissect representative communication protocols and analyze the associated security risks, indicating the communication layer in which each risk originates.

- 🛡️ **Defensive Outlook:** We discuss potential defense strategies tailored to each identified risk.

- 🔍 **Empirical Demonstration:** We further conduct experiments on MCP and A2A to reveal novel vulnerabilities arising in real agent communication systems.

- 🚀 **Future Directions:** Finally, we outline open challenges and promising research opportunities in this rapidly evolving field.

</p>


<p align="justify">
We will continue to maintain and update this curated list of related papers and resources in this repository.
</p>

<p align="center">
  <img src="agentcommunication.png" width="1200"/>
</p>

<hr/>
<!--
## 📘 Collections
- [Survey](collection/survey.md)
- Paper&Report
    - A. User-Agent-Interaction
        - Protocols
            - [User-Agent-Interaction-Protocols](collection/paper&report/user-agent-interaction/protocols/user-agent-interaction-protocols.md)
        - Risks
            - [Risks-from-L1](collection/paper&report/user-agent-interaction/risks/risks-from-L1.md)
            - [Risks-from-L2](collection/paper&report/user-agent-interaction/risks/risks-from-L2.md)
            - [Risks-from-L3](collection/paper&report/user-agent-interaction/risks/risks-from-L3.md)
        - Defenses
            - [Defenses-on-L1](collection/paper&report/user-agent-interaction/defenses/defenses-on-L1.md)
            - [Defenses-on-L2](collection/paper&report/user-agent-interaction/defenses/defenses-on-L2.md)
            - [Defenses-on-L3](collection/paper&report/user-agent-interaction/defenses/defenses-on-L3.md)
    - B. Agent-Agent-Communication
        - Protocols
            - [CS-based-Communication-Protocols](collection/paper&report/agent-agent-communication/protocols/cs-based-communication-protocols.md)
            - [P2P-based-Communication-Protocols](collection/paper&report/agent-agent-communication/protocols/p2p-based-communication-protocols.md)
            - [Hybrid-Communication-Protocols](collection/paper&report/agent-agent-communication/protocols/hybrid-communication-protocols.md)
            - [Other-Communication-Protocols](collection/paper&report/agent-agent-communication/protocols/other-communication-protocols.md)
        - Risks
            - [Risks-from-L1](collection/paper&report/agent-agent-communication/risks/risks-from-L1.md)
            - [Risks-from-L2](collection/paper&report/agent-agent-communication/risks/risks-from-L2.md)
            - [Risks-from-L3](collection/paper&report/agent-agent-communication/risks/risks-from-L3.md)
        - Defenses
            - [Defenses-on-L1](collection/paper&report/agent-agent-communication/defenses/defenses-on-L1.md)
            - [Defenses-on-L2](collection/paper&report/agent-agent-communication/defenses/defenses-on-L2.md)
            - [Defenses-on-L3](collection/paper&report/agent-agent-communication/defenses/defenses-on-L3.md)
    - C. Agent-Environment-Communication
        - Protocols
            - [Agent-Environment-Communication-Protocols](collection/paper&report/agent-environment-communication/protocols/agent-environment-communication-protocols.md)
        - Risks
            - [Risks-from-L1](collection/paper&report/agent-environment-communication/risks/risks-from-L1.md)
            - [Risks-from-L2](collection/paper&report/agent-environment-communication/risks/risks-from-L2.md)
            - [Risks-from-L3](collection/paper&report/agent-environment-communication/risks/risks-from-L3.md)
        - Defenses
            - [Defenses-on-L1](collection/paper&report/agent-environment-communication/defenses/defenses-on-L1.md)
            - [Defenses-on-L2](collection/paper&report/agent-environment-communication/defenses/defenses-on-L2.md)
            - [Defenses-on-L3](collection/paper&report/agent-environment-communication/defenses/defenses-on-L3.md)
<hr/>
-->

## 🧩 Communication–Layer Collections Matrix



<!--
| **Layer ↓ / Mode →**                                                          | **User ↔ Agent** | **Agent ↔ Agent** | **Agent ↔ Environment** |
|-------------------------------------------------------------------------------|------------------|-------------------|--------------------------|
| **Protocol (Mode-level)**                                                          | [User-Agent-Interaction-Protocols](collection/paper&report/user-agent-interaction/protocols/user-agent-interaction-protocols.md) | [CS-based](collection/paper&report/agent-agent-communication/protocols/cs-based-communication-protocols.md), [P2P-based](collection/paper&report/agent-agent-communication/protocols/p2p-based-communication-protocols.md), [Hybrid](collection/paper&report/agent-agent-communication/protocols/hybrid-communication-protocols.md), [Others](collection/paper&report/agent-agent-communication/protocols/other-communication-protocols.md) | [Agent-Environment-Communication-Protocols](collection/paper&report/agent-environment-communication/protocols/agent-environment-communication-protocols.md) |
| **🔵 L1 — Transmission Layer**                                                          | [Risks-from-L1](collection/paper&report/user-agent-interaction/risks/risks-from-L1.md) <hr> [Defenses-on-L1](collection/paper&report/user-agent-interaction/defenses/defenses-on-L1.md) | [Risks-from-L1](collection/paper&report/agent-agent-communication/risks/risks-from-L1.md) <hr> [Defenses-on-L1](collection/paper&report/agent-agent-communication/defenses/defenses-on-L1.md) | [Risks-from-L1](collection/paper&report/agent-environment-communication/risks/risks-from-L1.md) <hr> [Defenses-on-L1](collection/paper&report/agent-environment-communication/defenses/defenses-on-L1.md) |
| **🟣 L2 — Semantics Layer**                                                          | [Risks-from-L2](collection/paper&report/user-agent-interaction/risks/risks-from-L2.md) <hr> [Defenses-on-L2](collection/paper&report/user-agent-interaction/defenses/defenses-on-L2.md) | [Risks-from-L2](collection/paper&report/agent-agent-communication/risks/risks-from-L2.md) <hr> [Defenses-on-L2](collection/paper&report/agent-agent-communication/defenses/defenses-on-L2.md) | [Risks-from-L2](collection/paper&report/agent-environment-communication/risks/risks-from-L2.md) <hr> [Defenses-on-L2](collection/paper&report/agent-environment-communication/defenses/defenses-on-L2.md) |
| **🔶 L3 — Orchestration Layer**                                                          | [Risks-from-L3](collection/paper&report/user-agent-interaction/risks/risks-from-L3.md) <hr> [Defenses-on-L3](collection/paper&report/user-agent-interaction/defenses/defenses-on-L3.md) | [Risks-from-L3](collection/paper&report/agent-agent-communication/risks/risks-from-L3.md) <hr> [Defenses-on-L3](collection/paper&report/agent-agent-communication/defenses/defenses-on-L3.md) | [Risks-from-L3](collection/paper&report/agent-environment-communication/risks/risks-from-L3.md) <hr> [Defenses-on-L3](collection/paper&report/agent-environment-communication/defenses/defenses-on-L3.md) |
-->

<table>
  <thead>
    <tr>
      <th style="text-align:center;">
        Layer ↓ / Mode → 
      </th>
      <th style="text-align:center;">User ↔ Agent</th>
      <th style="text-align:center;">Agent ↔ Agent</th>
      <th style="text-align:center;">Agent ↔ Environment</th>
    </tr>
  </thead>

  <tbody>
    <!-- Protocol row -->
    <tr>
      <th style="text-align:center;">Protocol (Mode-level)</th>
      <td><a href="collection/paper&report/user-agent-interaction/protocols/user-agent-interaction-protocols.md">User-Agent-Interaction-Protocols</a></td>
      <td>
        <a href="collection/paper&report/agent-agent-communication/protocols/cs-based-communication-protocols.md">CS-based</a>,
        <a href="collection/paper&report/agent-agent-communication/protocols/p2p-based-communication-protocols.md">P2P-based</a>,
        <a href="collection/paper&report/agent-agent-communication/protocols/hybrid-communication-protocols.md">Hybrid</a>,
        <a href="collection/paper&report/agent-agent-communication/protocols/other-communication-protocols.md">Others</a>
      </td>
      <td><a href="collection/paper&report/agent-environment-communication/protocols/agent-environment-communication-protocols.md">Agent-Environment-Communication-Protocols</a></td>
    </tr>

<!-- L1 -->
<tr>
  <th style="text-align:center;">🔵 L1 — Data Transmission Layer</th>
  <td>
    <div><b>Risk:</b> <a href="collection/paper&report/user-agent-interaction/risks/risks-from-L1.md">Risks-from-L1</a></div>
    <div style="border-top: 1px solid #30363d; margin: 4px 0;"></div>
    <div><b>Defense:</b> <a href="collection/paper&report/user-agent-interaction/defenses/defenses-on-L1.md">Defenses-on-L1</a></div>
  </td>
  <td>
    <div><b>Risk:</b> <a href="collection/paper&report/agent-agent-communication/risks/risks-from-L1.md">Risks-from-L1</a></div>
    <hr>
    <div><b>Defense:</b> <a href="collection/paper&report/agent-agent-communication/defenses/defenses-on-L1.md">Defenses-on-L1</a></div>
  </td>
  <td>
    <div><b>Risk:</b> <a href="collection/paper&report/agent-environment-communication/risks/risks-from-L1.md">Risks-from-L1</a></div>
    <hr>
    <div><b>Defense:</b> <a href="collection/paper&report/agent-environment-communication/defenses/defenses-on-L1.md">Defenses-on-L1</a></div>
  </td>
</tr>

<!-- L2 -->
<tr>
  <th style="text-align:center;">🟣 L2 — Interaction Protocol Layer</th>
  <td>
    <div><b>Risk:</b> <a href="collection/paper&report/user-agent-interaction/risks/risks-from-L2.md">Risks-from-L2</a></div>
    <hr>
    <div><b>Defense:</b> <a href="collection/paper&report/user-agent-interaction/defenses/defenses-on-L2.md">Defenses-on-L2</a></div>
  </td>
  <td>
    <div><b>Risk:</b> <a href="collection/paper&report/agent-agent-communication/risks/risks-from-L2.md">Risks-from-L2</a></div>
    <hr>
    <div><b>Defense:</b> <a href="collection/paper&report/agent-agent-communication/defenses/defenses-on-L2.md">Defenses-on-L2</a></div>
  </td>
  <td>
    <div><b>Risk:</b> <a href="collection/paper&report/agent-environment-communication/risks/risks-from-L2.md">Risks-from-L2</a></div>
    <hr>
    <div><b>Defense:</b> <a href="collection/paper&report/agent-environment-communication/defenses/defenses-on-L2.md">Defenses-on-L2</a></div>
  </td>
</tr>

<!-- L3 -->
<tr>
  <th style="text-align:center;">🔶 L3 — Semantic Interpretation Layer</th>
  <td>
    <div><b>Risk:</b> <a href="collection/paper&report/user-agent-interaction/risks/risks-from-L3.md">Risks-from-L3</a></div>
    <hr>
    <div><b>Defense:</b> <a href="collection/paper&report/user-agent-interaction/defenses/defenses-on-L3.md">Defenses-on-L3</a></div>
  </td>
  <td>
    <div><b>Risk:</b> <a href="collection/paper&report/agent-agent-communication/risks/risks-from-L3.md">Risks-from-L3</a></div>
    <hr>
    <div><b>Defense:</b> <a href="collection/paper&report/agent-agent-communication/defenses/defenses-on-L3.md">Defenses-on-L3</a></div>
  </td>
  <td>
    <div><b>Risk:</b> <a href="collection/paper&report/agent-environment-communication/risks/risks-from-L3.md">Risks-from-L3</a></div>
    <hr>
    <div><b>Defense:</b> <a href="collection/paper&report/agent-environment-communication/defenses/defenses-on-L3.md">Defenses-on-L3</a></div>
  </td>
</tr>


  </tbody>
</table>




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
