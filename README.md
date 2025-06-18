# Vertex AI Support Bot Demo

**Cloud-native, agent-based solution for Data Science support automation using Vertex AI and Python.**
Built and maintained by [Baure Jinjini Tech](https://github.com/engenhariabaurejinjinitech).

---

## 🚀 Project Overview

This repository demonstrates how to build a modular, multi-agent support bot using:
- **Google Cloud Vertex AI** (pipelines, endpoints)
- **Python agents** for trend fetching, analysis, and support automation
- Integrations with Google Trends, social media APIs, and custom NLP

### Example Use Cases
- Real-time customer trend analysis from Google and social channels
- Automated support responses based on trending topics
- Data-driven insights for marketing, retail, or SaaS businesses

---

## 📁 Structure

```
agent/              # Python modules (trend_fetch, analysis, support)
notebooks/          # Demo Jupyter notebooks
pipeline/           # Vertex AI pipeline definitions (YAML)
sample_data/        # Test queries and sample data
requirements.txt    # Python dependencies
.gitignore
LICENSE
README.md
```

---

## 🛠️ Getting Started

**Clone the repo:**
```bash
git clone https://github.com/engenhariabaurejinjinitech/demos.git
cd demos
```

**Install dependencies:**
```bash
pip install -r requirements.txt
```

**Try the demo notebook:**
- Open `notebooks/VertexAI_Demo.ipynb` in Jupyter or Colab

**Run agents locally:**
- See examples in `agent/` for running trend fetch and analysis

---

## 🧩 How It Works

- `agent/trend_fetch_agent.py`: Pulls trend data from APIs (Google Trends, Meta, etc.)
- `agent/trend_analysis_agent.py`: Analyzes/summarizes trends using ML/NLP
- `agent/support_response_agent.py`: Responds to user queries with actionable insights
- `pipeline/vertex_pipeline.yaml`: (Optional) Run the workflow as a managed Vertex AI pipeline

---

## 🤝 Contributing

Pull requests, issues, and feature suggestions are welcome!
Open an issue or fork and submit a PR.

---

## 📄 License

MIT License — see `LICENSE` for details.

---

*Created with ❤️ by Baure Jinjini Tech.*
