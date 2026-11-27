# Hi, I'm Sriteja Madishetty 👋

**Data Science Engineer @ American Express · Generative AI · MLOps** — Scottsdale, AZ

I build LLM systems that hold up outside the demo: retrieval pipelines, fine-tuned models, and now **AI agents with guardrails enforced in code**. Before my M.P.S. in Data Science at UMBC, I spent over three years in DevOps and data engineering at Wipro and HCLTech, which is why I care about CI, monitoring and things that fail safely.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-sritejamadishetty-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sritejamadishetty/)
[![Medium](https://img.shields.io/badge/Medium-@madishetty8-000000?logo=medium&logoColor=white)](https://medium.com/@madishetty8)

---

## 🛠 Featured: [agent-skills](https://github.com/Sritejam/agent-skills)

Claude Code skills for building AI agents the disciplined way. **agent-architect** takes you from an idea to a tested project:

**Interview → Decide (do you even need an agent?) → Architect (approval gate) → Scaffold → Verify (audit + evals) → Hand off**

- Pushes back when a single call or a workflow is enough
- Generates projects from 6 vetted patterns (Anthropic SDK, Claude Agent SDK, MCP server)
- Guardrails live in code: turn and budget caps, a PreToolUse guard, transient-only retries, `stop_reason`-aware output validation
- A static audit and frozen evals (representative, boundary, adversarial) decide when it's done

```bash
git clone https://github.com/Sritejam/agent-skills
cp -r agent-skills/agent-architect ~/.claude/skills/
```

---

## 📊 Selected projects

| Project | Highlights | Stack |
|---|---|---|
| [**Treatment prediction from clinical notes**](https://github.com/Sritejam/Predicting_Treatments) | Team capstone; I led modelling. Fine-tuned ClinicalBERT to predict treatments across 12 imbalanced classes: **0.95 weighted F1**, up from 0.93 for a tuned TF-IDF + SVM | Python, ClinicalBERT, Hugging Face, scikit-learn, SMOTE |
| **Hybrid RAG for university Q&A** | FAISS vector search + BM25 + BERT re-ranking over custom semantic chunks with metadata tagging for privacy; **BERTScore F1 0.88** | Python, GPT-3.5, FAISS, BM25, BERT |
| [**Employee attrition with 500 labels**](https://github.com/Sritejam/Employee_Attritioin_Prediction) | Semi-supervised: PCA + K-Means++ into 498 clusters, one expert label per cluster for 7,500 unlabelled employees; **81.9% test F1** | Python, scikit-learn |

---

## 💼 Experience

| Role | Company | Dates |
|---|---|---|
| **Engineer II** (Data Science Engineer) | **American Express** | 2025 – present |
| Senior Software Engineer | HCLTech, Hyderabad | 2022 |
| Project Engineer | Wipro, Pune | 2019 – 2022 |

Before American Express: SQL/ETL pipelines for financial reporting, anomaly detection for transaction inconsistencies, Tableau dashboards, Jenkins CI/CD with SonarQube, Red Hat Linux operations, ELK monitoring, and lots of Shell/Python automation.

## 🎓 Education

- **M.P.S. Data Science**, University of Maryland, Baltimore County (2023 – 2024)
- **Technology Entrepreneurship Programme**, Indian School of Business (2017 – 2019)
- **B.Tech Computer Science**, Malla Reddy Engineering College, Hyderabad (2015 – 2019)

## 📜 Certifications

Oracle Cloud Infrastructure 2024 Generative AI Professional · AI Agents Development · Docker · Kubernetes · Ansible

---

## 🧰 Toolbox

- **AI / LLMs:** Claude & Anthropic SDK · Claude Agent SDK · MCP · Hugging Face Transformers · RAG (FAISS, BM25) · fine-tuning
- **ML & data:** Python · SQL · pandas · scikit-learn · PyTorch · TensorFlow · PySpark · Tableau
- **Cloud & MLOps:** AWS (SageMaker, Bedrock, Glue, Lambda, S3) · Docker · Kubernetes · Ansible · Jenkins · GitLab CI · MLflow · ELK
