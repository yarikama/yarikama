<h1 align="center">Henry Hsu</h1>

<p align="center">
  <em>Building production GenAI systems.</em><br/>
  Previously led GenAI at <a href="https://docs.maiagent.ai/maiagent-user-guide/maiagent-user-guide-en/">MaiAgent</a> (scaled users 3K → 20K) · <a href="https://github.com/run-llama/llama_index/pulls?q=is%3Apr+author%3Ayarikama+is%3Amerged">LlamaIndex contributor (14 merged PRs)</a> · M.C.S. @ Rice · <strong>SWE Intern @ Google (Summer 2026)</strong>
</p>

<p align="center">
  <a href="https://www.yarikama.com/"><img src="https://img.shields.io/badge/Portfolio-yarikama.com-1f6feb?style=flat-square" alt="portfolio"/></a>
  <a href="https://www.linkedin.com/in/yarikama/"><img src="https://img.shields.io/badge/LinkedIn-yarikama-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="linkedin"/></a>
  <a href="mailto:hsuhengjui@gmail.com"><img src="https://img.shields.io/badge/Email-hsuhengjui%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="email"/></a>
</p>

---

### About

Former **GenAI Team Lead** who shipped Agentic AI Systems, Advanced RAG, and the backend infrastructure behind a B2B platform serving CTBC Bank, MSI, HPE, and iGroup — work that contributed to a **Presidential Hackathon win (2024, Top 5 nationally)** and the **23rd Golden Peak Award (2025)**. I care about systems that survive contact with real users: retrieval that scales past 20M+ chunks, agents that don't burn tokens, and test coverage that catches regressions before they ship.

This summer I interned at **Google** as a SWE, building integration-test infrastructure from zero and an LLM agent that triages failing test runs. Now finishing an M.C.S. at Rice (GPA 4.00, graduating Dec. 2026).

---

### Featured Work

<table>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://www.yarikama.com/">☸️ yarikama.com</a></h4>
      <sub><em>k3s · Argo CD · vLLM · FastAPI · React</em></sub>
      <p>My site, run end to end on a home k3s cluster: GitHub Actions runs <strong>208</strong> tests and Argo CD rolls out in ~5 min with zero downtime, watched by Prometheus, Grafana, Loki and Tempo. Two self-hosted LLMs share one 8 GB GPU: a cited Q&amp;A chat whose prefix caching cuts time to first token on an 8k-token prompt from <strong>3.9 s to 0.17 s</strong>, and an editor autocomplete. <a href="https://github.com/yarikama/portfolio-back-end">Code</a></p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/yarikama/PAPIT">🔍 Prompt-Aware Image Token Pruning</a></h4>
      <sub><em>PyTorch · LLaVA · CLIP · Knowledge Distillation</em></sub>
      <p>Distilled LLaVA-1.5-7B's own attention into a <strong>1.3M-parameter</strong> scorer that drops the image patches the LLM would ignore: <strong>10×</strong> less attention compute at a quarter of the tokens, TextVQA accuracy close to the full model (36.0 vs. 36.7), and <strong>0.43 ms</strong> per image to decide what to keep.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/yarikama/GGJSSP">📐 Cross-Size GNN Job Shop Scheduling</a></h4>
      <sub><em>PyTorch · Graph Neural Networks · GRPO</em></sub>
      <p>Traced why GNN schedulers trained on 10×10 instances collapse on larger ones (<strong>136%</strong> relative error for sum aggregation vs. 26% for mean on Taillard 15×15) to machine-conflict degree growing with the job count, then showed in a 5-seed factorial that degree-normalized aggregation and machine-hub routing both bring zero-shot error to about <strong>26%</strong> on instances up to 100×20.</p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/yarikama/Agentic-Advanced-RAG">🧠 Agentic Hybrid RAG</a></h4>
      <sub><em>LangGraph · CrewAI · Neo4j · Milvus</em></sub>
      <p>LangGraph agent that routes each question to no retrieval, global search over Neo4j community summaries, or local entity search, backing every retrieval path with Milvus hybrid search. Reached <strong>88.2% MAR@10</strong> on multi-hop questions, and cut indexing token cost by <strong>35%</strong> (for 2.56% worse RAGAS) by clustering the vector store.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/run-llama/llama_index/pulls?q=is%3Apr+author%3Ayarikama+is%3Amerged">🦙 LlamaIndex Contributions</a></h4>
      <sub><em>Open Source · 15K+ ⭐</em></sub>
      <p><strong>14 merged PRs</strong> across AWS Bedrock, Claude, Elasticsearch, Cohere, OpenAI, MCP Client, and the AI Agent Workflow modules — bug fixes, new integrations, and capability extensions.</p>
    </td>
    <td width="50%" valign="top">
      <h4>🚀 MaiAgent Production Platform</h4>
      <sub><em>Django · FastAPI · LlamaIndex · AWS</em></sub>
      <p>Led GenAI roadmap for a 10-person startup. Upgraded chatbots into AI agents with memory + tools + MCP, driving <strong>120% partner growth</strong> and <strong>67%+</strong> token reduction. Introduced pytest framework reaching <strong>67% coverage</strong> from zero.</p>
    </td>
  </tr>
</table>

---

### Tech I Reach For

```text
Languages    Python · TypeScript · C/C++ · Java
Backend      Django · FastAPI · Express · Celery · Nginx
GenAI        LlamaIndex · LangChain · LangGraph · MCP · vLLM
Data         PostgreSQL · Neo4j · Milvus · Elasticsearch · MongoDB · Redis · Chroma
ML / DL      PyTorch · JAX · scikit-learn · NumPy · Pandas
Cloud        AWS (Bedrock · SageMaker · EMR · EC2 · S3 · RDS · ElastiCache)
DevOps       Docker · Kubernetes (k3s) · Argo CD · GitHub Actions · Prometheus · Grafana · Linux
Testing      pytest · JUnit · Vitest
```

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,typescript,cpp,java,django,fastapi,react,postgres,mongodb,redis,pytorch,aws,docker,kubernetes,linux,git,neovim,bash" alt="tech stack"/>
</p>

---

### GitHub

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=yarikama&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=dracula&locale=en&hide_border=false&order=1" height="150" alt="stats graph"  />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=yarikama&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=false&order=2" height="150" alt="languages graph"  />
</div>

<img src="https://raw.githubusercontent.com/yarikama/yarikama/output/snake.svg" alt="Personal GitHub Contribution Graph" />
