# Hi, I'm Sriteja Madishetty 👋

**Data Scientist · Generative AI · MLOps** — based in Phoenix, AZ

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
| [**Treatment prediction from clinical notes**](https://github.com/Sritejam/Predicting_Treatments) | Fine-tuned Clinical BERT to identify treatments in clinical notes; **94% weighted F1** on highly imbalanced data (SMOTE + stratified sampling), beating an SVM baseline | Python, Clinical BERT, Hugging Face, SMOTE |
| **Hybrid RAG for university Q&A** | FAISS vector search + BM25 + BERT re-ranking over custom semantic chunks with metadata tagging for privacy; **BERTScore F1 0.88** | Python, GPT-3.5, FAISS, BM25, BERT |
| [**Employee attrition analysis**](https://github.com/Sritejam/Employee_Attritioin_Prediction) | Unsupervised pipeline with PCA, K-Means and DBSCAN, built with SME guidance; **86% weighted F1** | Python, scikit-learn, Streamlit |

---

## 💼 Experience

| Role | Company | Dates |
|---|---|---|
| Senior Software Engineer | HCLTech, Hyderabad | 2022 |
| Project Engineer | Wipro, Pune | 2019 – 2022 |

SQL/ETL pipelines for financial reporting, anomaly detection for transaction inconsistencies, Tableau dashboards, Jenkins CI/CD with SonarQube, Red Hat Linux operations, ELK monitoring, and lots of Shell/Python automation.

## 🎓 Education & certification

- **M.P.S. Data Science**, University of Maryland, Baltimore County (2023 – 2024)
- **B.Tech Computer Science**, Malla Reddy Engineering College, Hyderabad (2015 – 2019)
- **Oracle Cloud Infrastructure 2024 Generative AI Professional** (2024)

---

## 🧰 Toolbox

- **AI / LLMs:** Claude & Anthropic SDK · Claude Agent SDK · MCP · Hugging Face Transformers · RAG (FAISS, BM25) · fine-tuning
- **ML & data:** Python · SQL · pandas · scikit-learn · PyTorch · TensorFlow · PySpark · Tableau
- **Cloud & MLOps:** AWS (SageMaker, Bedrock, Glue, Lambda, S3) · Docker · Jenkins · GitLab CI · MLflow · ELK
