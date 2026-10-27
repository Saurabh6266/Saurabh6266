<h1 align="center">Saurabh Gupta</h1>

<p align="center">
  Applied ML researcher · Computer vision, explainable ML and LLM reliability<br>
  B.Tech, Mineral & Metallurgical Engineering (Minor in Mathematics and Computing) · IIT (ISM) Dhanbad · 2024–2028
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/saurabhguptaml"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:saurabh.iitian62@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white"/></a>
  <a href="https://huggingface.co/saurabh0962"><img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black"/></a>
</p>

---

## About me

I'm an undergraduate student in Mineral & Metallurgical Engineering at IIT (ISM) Dhanbad who came to machine learning through metallurgy. I wanted models that could be checked against the physics of the process they describe, so I started building them: a vision model for scrap grading, a viscosity predictor for blast furnace slag, and benchmarks that test whether language models respect physical constraints.

I am self-taught in ML, and the work below is where I learned it. I try to state each project's limits next to its results.

## What I work on

- **Computer vision for industry:** classifying scrap and detecting contamination from images, with attention maps (Score-CAM) so a human can see what the model looked at.
- **Explainable ML for process data:** predicting process properties from composition and explaining each prediction in terms an operator can act on.
- **Reliability of language models:** testing whether LLMs notice physically impossible inputs, and how multi-agent LLM systems behave when one agent is deceptive.

## Currently

- **Adversarial robustness in multi-agent LLM systems.** I am a co-author on a paper by a team of four at Dubai Computer Science Society. I trained LoRA adapters to test a pre-commitment mitigation against deceptive peer agents, built the data pipeline that restructures benchmark data into the mitigation's format, and contributed to the experimental design and cross-model comparisons. It is in preparation for arXiv and an AI-safety workshop.
- **MANI** (ML Research Fellow, Aug 2026 – present): ML for automated manufacturing systems.
- Building **MetallurgyBench**, an LLM evaluation benchmark for industrial materials science reasoning (in progress)

## Projects

| Project | What it is | Status and results |
|---|---|---|
| [ScrapScan](https://github.com/Saurabh6266/scrapscan) · [demo](https://scrapscan-771p.onrender.com) | Multi-task EfficientNet-B0 for scrap grading and zinc contamination detection; exported to ONNX for in-browser inference; Score-CAM for explanations | Top 25 at IIM MATRIx 2026; Finalist at PitchFund 2026 |
| [SLPB-50](https://github.com/Saurabh6266/slag-plausibility-eval) · [dataset](https://huggingface.co/datasets/saurabh0962/slag-plausibility-eval) | Slag Physical Plausibility Benchmark: 50 matched pairs of valid and physically impossible pyrometallurgy statements, 5 categories, 3 phrasings each (300 prompts) | Gemma 3 4B (4-bit) missed 48% of planted errors. Pilot only: one model, one domain |
| [Blast Furnace Slag Viscosity Controller](https://github.com/Saurabh6266/dcg-slag-viscosity-controller) | CatBoost, XGBoost and DNN regressors on CaO, SiO₂, Al₂O₃ and MgO, with SHAP attribution and a Qwen2.5-7B layer that writes plain-language operator recommendations | 0.9723 R² with Optuna-tuned CatBoost, on **simulated metallurgical** data. A prototype, not a plant-validated model |
| [MetallurgyBench](https://github.com/Saurabh6266/MetallurgyBench) | Benchmark for LLM reasoning on industrial materials science | In progress |

Other projects: FIFA World Cup 2026 Monte Carlo Engine · Credit Card Fraud Detection · F1 Pit-Stop Duration Prediction

## Tools I use

| | |
|---|---|
| **Languages** | Python, C++, SQL |
| **ML / DL** | PyTorch, TensorFlow, scikit-learn, XGBoost, CatBoost, Optuna, SHAP |
| **Vision** | EfficientNet, OpenCV, Score-CAM, ONNX |
| **LLMs** | Hugging Face Transformers, LoRA fine-tuning, Qwen2.5, Gemma 3 |
| **Workflow** | Git, Gradio, Hugging Face Spaces, Google Colab |

## Highlights

- **Top 25** — IIM MATRIXx 2026 Startup Hackathon (IIT Hyderabad) · ScrapScan · Mentorship from a JSW Steel R&D Researcher
- **Finalist** - PitchFund 2026 (E-Summit, IIT (ISM)) · ScrapScan · Pitched to a panel of investors
- **CodeChef** max rating 1526 · Global rank 646 in Starters 227 (40K+ participants)
- **AlgoUtsav 2026** — Rank 151 / 2,500+ teams (NIT Rourkela)
- **Gold Medal** — General Championship Inter-Hostel Volleyball Tournament, IIT (ISM) Dhanbad (libero)

## Where I am headed

- **Next:** research internships in summer 2027 in ML for scientific and industrial problems, and in LLM evaluation and reliability.
- **After that:** a Master's in mathematics and machine learning. I want the formal grounding in statistics and learning theory that my project work has made me want more of.
- **Longer term:** research on reliable ML for physical and industrial systems, in an academic or industry lab.

## Get in touch

I am open to research collaborations, internships and open-source work in ML for materials, manufacturing and LLM evaluation.
📧 saurabh.iitian62@gmail.com · [LinkedIn](https://www.linkedin.com/in/saurabhguptaml) · [Hugging Face](https://huggingface.co/saurabh0962)
