# eos-analysis-template

This repository provides a structured template for setting up new research analysis in Ersilia. 

Replace this description with a N-word description of the project, following the FAIR (link) principles holded by Ersilia.  


Tracked by Git and linked to a Github repository: only src, scripts and notebooks

Tracked by DVC and linked to a Google Drive folder inside "Projects/<<Project name>>" named "Repository"



## Repository Structure

eos-analysis-template/
│
├── LICENSE
├── README.md
├── .gitignore
├── install.sh
├── requirements.txt
│
├── data/
│   ├── raw/
│   └── processed/
│
├── scripts/
├── notebooks/
├── assets/
├── output/
│   ├── results/
│   └── plots/
│
├── src/
├── tools/
├── docs/
├── tmp/
│
└── .git/


# Repository Structure

This repository is organized as follows:

- **data/**
  - **raw/** → Original, untouched datasets  
  - **processed/** → Cleaned and transformed datasets  

- **scripts/** → Standalone scripts for preprocessing or automation  

- **notebooks/** → Jupyter notebooks for exploration and prototyping  

- **assets/** → Images, figures, and other static resources  

- **output/**
  - **results/** → Numerical results, logs, or text outputs  
  - **plots/** → Visualizations and charts  

- **src/** → Core source code and reusable modules  

- **tools/** → Helper utilities and development tools  

- **docs/** → Project documentation and reports  

- **tmp/** → Temporary files or intermediate outputs  

- **.git/** → Git metadata (version control)  

---

📌 Empty folders are preserved with `.gitkeep` files so the structure remains consistent in Git.


---

## Project motivation and goal

Write a brief description about the scientific motivation and goal of the project. 

## 🚀 Getting Started

1. **Clone this repository**  
   ```bash
   git clone <your-repo-url>
   cd eos-analysis-template
