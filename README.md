# Stanislav Elkin

**Senior AI/ML Engineer · Production LLM/RAG · NLP · AI Security · Agentic Systems**

I build production-oriented AI systems that move beyond demos: retrieval workflows, LLM/RAG applications, NLP classifiers, evaluation pipelines, inference optimization, and agentic systems with measurable behavior.

My strongest areas are applied AI engineering, production NLP, retrieval-augmented systems, adversarial/deceptive-content detection, and reliable ML deployment.

<p>
  <a href="https://www.linkedin.com/in/stanislav-elkin">
    <img src="https://img.shields.io/badge/LinkedIn-Stanislav%20Elkin-blue?style=flat-square&logo=linkedin" />
  </a>
  <a href="https://scholar.google.com/citations?user=no8waPIAAAAJ&hl=en">
    <img src="https://img.shields.io/badge/Google%20Scholar-Publications-grey?style=flat-square&logo=googlescholar" />
  </a>
  <a href="https://orcid.org/0009-0001-2989-9262">
    <img src="https://img.shields.io/badge/ORCID-0009--0001--2989--9262-green?style=flat-square&logo=orcid" />
  </a>
  <a href="mailto:stanislavelkin.br@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-red?style=flat-square&logo=gmail" />
  </a>
</p>

---

## Current Focus

* Production LLM/RAG systems over heterogeneous documents and knowledge sources
* Agentic AI workflows with controlled tool use, structured outputs, and evaluation
* Scam, fraud, and social-engineering detection in messaging and communication data
* Retrieval quality, reranking, prompt design, LLM evaluation, and release validation
* AI security research: adversarial robustness and behavior-based detection

---

## Technical Stack

| Area               | Tools & Experience                                                                                              |
| ------------------ | --------------------------------------------------------------------------------------------------------------- |
| LLM / RAG          | LangGraph, LangChain-style workflows, Anthropic Claude, OpenAI API, RAG evaluation, LLM-as-judge, prompt design |
| Retrieval & Search | BM25, dense embeddings, reranking, FAISS, Elasticsearch, Milvus, Redis, hybrid retrieval                        |
| Machine Learning   | PyTorch, Hugging Face, BERT/T5, classifiers, detection systems, evaluation protocols                            |
| Agentic AI         | Multi-agent workflows, controlled tool invocation, graph memory, typed state, reasoning traces                  |
| Backend / Infra    | Python, FastAPI, Docker, CI/CD, pytest, REST APIs, async workflows                                              |
| Optimization       | ONNX, TensorRT, Triton, inference latency and throughput optimization                                           |
| Knowledge Graphs   | NetworkX, RDF/OWL, SPARQL, ontology design, entity extraction, relationship modeling                            |
| Data               | Pandas, NumPy, SQL, data cleaning, dataset construction, synthetic data, hard negatives                         |

---

## Selected Impact

* Built production-oriented NLP/LLM systems for document intelligence, retrieval, and real-time deceptive-content detection.
* Improved ML inference performance with Triton, ONNX, and TensorRT: **6× throughput improvement** and around **40% lower latency**.
* Built a retrieval-augmented LLM agent for cybersecurity reasoning that improved task completion by **57.1% over a GPT-4o baseline** on a CTF benchmark.
* Published research on retrieval-augmented LLM agents for adversarial multi-step task automation at **IEEE FLLM 2025**.
* Published work on NLP systems for production speech pipelines at **Springer AIST 2024**.
* Mentored **12 engineers/students** on production ML system design, deployment, monitoring, testing, and MLOps practices.

---

## Featured Projects

### [cti-multi-agent](https://github.com/ElkinStas/cti-multi-agent)

Multi-agent cyber threat intelligence system that discovers cybersecurity incidents from the open web, extracts structured intelligence, enriches referenced CVEs through the NVD API, and serves consolidated JSON/Markdown reports via an async FastAPI service.

The pipeline is built as a LangGraph StateGraph with explicit agent-to-agent state transitions: search, extraction, post-processing, CVE enrichment, and report synthesis. The system includes Claude-based structured extraction, heuristic fallbacks, retry/backoff logic, per-node telemetry, caching, incident-to-CVE linkage, Docker setup, Streamlit UI, and a test suite that runs without network access or API keys.

**Focus:** LangGraph, FastAPI, Anthropic Claude, multi-agent workflows, structured outputs, CVE enrichment, telemetry, caching, Docker, Streamlit, pytest.

---

### [graph-generation-rl-task](https://github.com/ElkinStas/graph-generation-rl-task)

RL training task for teaching LLM agents to generate graphs that satisfy precise network topology constraints. The model must produce a connected 400-node graph matching target clustering coefficient, average path length, and connected-component constraints under limited tool-use and metric-call budgets.

What makes the task interesting is that there is no simple one-shot solution: the agent has to choose between graph generation strategies such as Erdős-Rényi, Barabási-Albert, and Holme-Kim triadic closure, then iteratively refine the graph through rewiring, triangle-boosting, and edge pruning. The benchmark is intentionally difficult because clustering and path length often trade off against each other, forcing the model to reason under constraints rather than simply generate code.

**Focus:** Python, NetworkX, reinforcement learning tasks, graph generation, constrained optimization, network metrics, tool-use budgets, LLM training evaluation.

---

### [CTF_Assistant](https://github.com/ElkinStas/CTF_Assistant)

Research codebase behind an IEEE FLLM 2025 paper on retrieval-augmented reasoning for offensive-security and CTF-style tasks. The project explores how an LLM agent can combine retrieval, graph-based memory, controlled tool routing, and step-by-step reasoning to solve multi-stage cybersecurity challenges more reliably than a raw LLM baseline.

The system uses an open-source LLM reasoning core, RAG over task-relevant data, NetworkX-based graph memory, and integrations with tools such as DirSearch, Nmap, SQLmap, Hashcat, and CyberChef. The dataset covers reconnaissance, forensics, cryptography, low-level exploitation, binary analysis, and reverse engineering tasks.

**Focus:** LLM agents, RAG, AI security, CTF automation, graph-based memory, tool routing, cybersecurity reasoning, IEEE FLLM 2025.

---

## Publications

* [**Retrieval-Augmented Reasoning for Offensive Security: A Multi-Agent LLM Framework for CTF Challenge Solving**](https://ieeexplore.ieee.org/document/11391064) — IEEE FLLM 2025
* [**Graphical Abbreviation Disclosure in Russian Language**](https://link.springer.com/chapter/10.1007/978-3-031-88036-0_3) — Springer AIST 2024

---

## About Me

I’m based in Brazil and work well in remote, async, cross-functional environments. I enjoy roles where AI is not just a prototype, but a reliable product component: measurable, testable, useful, and maintainable.

I’m especially interested in applied AI products, AI security, retrieval systems, developer tools, document intelligence, knowledge systems, and agentic workflows.

---

## Links

* [LinkedIn](https://www.linkedin.com/in/stanislav-elkin)
* [GitHub](https://github.com/ElkinStas)
* [Google Scholar](https://scholar.google.com/citations?user=no8waPIAAAAJ&hl=en)
* [ORCID](https://orcid.org/0009-0001-2989-9262)
