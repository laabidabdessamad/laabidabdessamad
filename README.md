<h1 align="center">Hi there, I'm Abdessamad 👋</h1>
<p align="center">Data scientist · Master's in Data Science and Analytics, Cadi Ayyad University (July 2026)</p>

<p align="center">
  <a href="https://www.linkedin.com/in/laabidabdessamad/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:i.laabidabdessamad@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>

---

### 🚀 What I've been building

**🧠 [Trading-signal deep learning](https://github.com/laabidabdessamad) — Master's thesis**
Trained and compared 8 deep learning architectures (LSTM, TCN, TFT, N-BEATS, N-HiTS, CDT-CNN, TiDE, xLSTM) as Buy/Hold/Sell classifiers across a 70-stock universe, under 5 class-imbalance strategies — 41 trained configurations, scored jointly on classification metrics and Sharpe ratio. The fix that maximized F1 also inflated trade count 4–8x and tanked risk-adjusted return — a disagreement a classification-only evaluation would have missed entirely.

**💳 [CreditLens](https://github.com/laabidabdessamad/creditlens)** — cost-sensitive credit-risk scoring
Tuned for expected cost (5:1 cost matrix) instead of accuracy on the German Credit dataset. Calibrated probabilities, a cost-optimal threshold picked on out-of-fold predictions, per-applicant SHAP explanations, and a Fairlearn audit that excludes sex and age at the API boundary. Reports its own uncertainty honestly — the saving over "decline everyone" has a 95% CI that includes zero.

**🚗 [Car insurance claim risk](https://github.com/laabidabdessamad/insurance-claim-ml-pipeline)** — classification + regression, deployed
Rebuilt a leaky notebook (preprocessing fit before the train/test split) into two proper sklearn pipelines: claim probability + claim size. Shipped behind FastAPI on AWS Fargate, provisioned with CDK, deployed only through GitHub Actions via OIDC — no long-lived AWS keys anywhere.

---

### 🛠️ Toolbox

<p>
<img src="https://skillicons.dev/icons?i=python,pytorch,sklearn,fastapi,docker,aws,github,git,vscode&theme=dark" />
</p>

**Modeling** — Python · PyTorch · scikit-learn · XGBoost · Optuna
**Explainability & fairness** — SHAP · Fairlearn
**Data & tracking** — Pandera · DVC · MLflow · Evidently
**Serving & deployment** — FastAPI · Streamlit · Docker · AWS (Fargate, CDK) · Terraform · GitHub Actions

---

### 📊 GitHub stats

<p align="center">
  <img height="165" src="https://github-stats-extended.vercel.app/api?username=laabidabdessamad&show_icons=true&theme=default&hide_border=true" />
  <img height="165" src="https://github-stats-extended.vercel.app/api?username=laabidabdessamad&layout=compact&hide_border=true" />
</p>

---

### 📫 Reach me

📧 i.laabidabdessamad@gmail.com · 💼 [linkedin.com/in/laabidabdessamad](https://www.linkedin.com/in/laabidabdessamad/)
