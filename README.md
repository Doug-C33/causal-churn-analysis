# causal-churn-impact

This project applies **causal inference techniques** to customer churn analysis using the **Telco Customer Churn dataset** from Kaggle. The goal is to derive **interpretable, causal business insights** by estimating the treatment effect of customer-related variables (e.g., contract type, tenure, payment method) on churn likelihood.

Beyond traditional modeling, this project integrates **LLM-based workflows** and builds a **LangChain agent** to automate insight generation from regression results.

---

## Objectives

- Ingest and clean real-world churn data
- Perform exploratory data analysis and baseline modeling
- Apply **Propensity Score Matching (PSM)** for causal estimation
- Use a **LangChain agent** to automate data-to-insight conversion
- Fine-tune a small **LLM** to produce human-readable executive summaries
- Build an interactive **Streamlit dashboard** for stakeholder use

---

## Tools & Technologies

- **Python**: `pandas`, `statsmodels`, `scikit-learn`, `matplotlib`, `seaborn`
- **Causal Inference**: Propensity Score Matching, ATT estimation
- **LLMs**: Phi-2 / DistilBERT (fine-tuned), Gemini API
- **LangChain**: Autonomous agent to trigger causal notebook & summarize outputs
- **Streamlit**: Web app for interactive report generation
- **Docker**: Containerization for deployment
- **Git & GitHub**: Version control and project hosting

---

## Project Structure



