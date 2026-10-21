# LLM Agents Reading List

Papers collected for the lab-meeting presentation on LLM agents, grouped by topic. Each entry lists the arXiv ID, first author, and title, with a one-line note on why it's on the list.

## LLM Agents and Tool Use

- **arXiv:2210.03629** — Shunyu Yao et al., *ReAct: Synergizing Reasoning and Acting in Language Models* — interleaves verbal reasoning traces with task-specific actions (e.g., Wikipedia API calls), reducing hallucination and error propagation on QA and interactive decision-making benchmarks.
- **arXiv:2302.04761** — Timo Schick et al., *Toolformer: Language Models Can Teach Themselves to Use Tools* — a model that self-supervisedly learns which APIs to call, when to call them, and how to fold results back into token prediction.
- **arXiv:2303.17580** — Yongliang Shen et al., *HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in Hugging Face* — uses an LLM as a controller that plans tasks, selects expert models from Hugging Face, executes them, and summarizes the results.
- **arXiv:2307.16789** — Yujia Qin et al., *ToolLLM: Facilitating Large Language Models to Master 16000+ Real-world APIs* — a general tool-use framework built on the ToolBench dataset (16,464 real-world APIs) with a depth-first-search reasoning strategy and an automatic evaluator (ToolEval).

## Retrieval-Augmented Generation

- **arXiv:2005.11401** — Patrick Lewis et al., *Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks* — the original RAG paper: a pre-trained seq2seq generator coupled with a dense Wikipedia retriever, trained end-to-end by marginalizing over retrieved documents.
- **arXiv:2310.11511** — Akari Asai et al., *Self-RAG: Learning to Retrieve, Generate, and Critique through Self-Reflection* — trains the LM to retrieve on demand and to critique retrieved passages and its own generations via reflection tokens.
- **arXiv:2312.10997** — Yunfan Gao et al., *Retrieval-Augmented Generation for Large Language Models: A Survey* — a systematic survey of the Naive / Advanced / Modular RAG paradigms, covering retrieval, generation, and augmentation techniques plus evaluation.
- **arXiv:2401.15884** — Shi-Qi Yan et al., *Corrective Retrieval Augmented Generation* — a lightweight retrieval evaluator that triggers corrective actions (web-search augmentation, decompose-then-recompose) when retrieval quality is poor.

## Multi-Agent Collaboration

- **arXiv:2308.00352** — Sirui Hong et al., *MetaGPT: Meta Programming for a Multi-Agent Collaborative Framework* — encodes Standardized Operating Procedures into prompt sequences and assigns assembly-line roles to agents, producing more coherent multi-agent software engineering solutions.
- **arXiv:2308.08155** — Qingyun Wu et al., *AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation* — an open-source framework of customizable, conversable agents (LLMs, humans, tools, or combinations) programmed with natural language and code.
- **arXiv:2308.10848** — Weize Chen et al., *AgentVerse: Facilitating Multi-Agent Collaboration and Exploring Emergent Behaviors* — orchestrates dynamic groups of expert agents that outperform single agents, and analyzes the emergent collaborative behaviors that arise.
