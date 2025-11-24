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


## 🧩 Communication–Layer Collections Matrix


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
  <td>
    <div><b>⚠️ </b> <a href="collection/paper&report/user-agent-interaction/risks/risks-from-L1.md">Risks-from-L1</a></div>
    <div><b>🛡️ </b> <a href="collection/paper&report/user-agent-interaction/defenses/defenses-on-L1.md">Defenses-on-L1</a></div>
  </td>
  <td>
    <div><b>⚠️ </b> <a href="collection/paper&report/agent-agent-communication/risks/risks-from-L1.md">Risks-from-L1</a></div>
    <div><b>🛡️ </b> <a href="collection/paper&report/agent-agent-communication/defenses/defenses-on-L1.md">Defenses-on-L1</a></div>
  </td>
  <td>
    <div><b>⚠️ </b> <a href="collection/paper&report/agent-environment-communication/risks/risks-from-L1.md">Risks-from-L1</a></div>
    <div><b>🛡️ </b> <a href="collection/paper&report/agent-environment-communication/defenses/defenses-on-L1.md">Defenses-on-L1</a></div>
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
    <div><b>📡 Protocols: </b>
      <a href="collection/paper&report/agent-agent-communication/protocols/cs-based-communication-protocols.md">CS-based</a>,
      <a href="collection/paper&report/agent-agent-communication/protocols/p2p-based-communication-protocols.md">P2P-based</a>,
      <a href="collection/paper&report/agent-agent-communication/protocols/hybrid-communication-protocols.md">Hybrid</a>,
      <a href="collection/paper&report/agent-agent-communication/protocols/other-communication-protocols.md">Others</a>
    </div>
    <div><b>⚠️ </b> <a href="collection/paper&report/agent-agent-communication/risks/risks-from-L2.md">Risks (attacks)</a></div>
    <div><b>🛡️ </b> <a href="collection/paper&report/agent-agent-communication/defenses/defenses-on-L2.md">Defenses</a></div>
  </td>

  <td>
    <div><b>📡 Protocols: </b><a href="collection/paper&report/agent-environment-communication/protocols/agent-environment-communication-protocols.md">Agent-Environment-Communication-Protocols</a></div>
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

<h2>🧰 Related Tools: Secure LLM Deployment</h2>

<p align="justify">
To support practical, end-to-end secure deployment of LLM-based agent systems, we have also developed an open-source security toolchain that is specifically designed for the secure deployment of LLMs, supporting features such as firewalls, access control, reverse proxy, and automatic blocking.
</p>

  <a href="https://github.com/IFRC-ZJU-Edu/SafeLLMDeploy">
    <img src="https://img.shields.io/badge/GitHub-Secure%20LLM%20Deployment-black?logo=github" height="28"/>
  </a>
  <a href="https://github.com/IFRC-ZJU-Edu/SafeLLMDeploy/stargazers">
    <img src="https://img.shields.io/github/stars/IFRC-ZJU-Edu/SafeLLMDeploy?color=yellow" height="28"/>
  </a>
  <a href="https://github.com/IFRC-ZJU-Edu/SafeLLMDeploy/issues">
    <img src="https://img.shields.io/badge/Issues-Welcome-blue" height="28"/>
  </a>



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
