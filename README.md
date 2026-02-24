## Project Summary

The project is an educational, hands-on workspace that combines:
- A detailed Unit 1 theory brief (`unit 1.txt`) covering AI/ML/DL/GenAI concepts, LLM architecture evolution, NLP fundamentals, and classical text classification.
- Practical notebooks (`PES2UG23CS629_HandsOn_1_Unit1.ipynb`, `PES2U2G23CS629_Project.ipynb`) intended for experimentation and course-based exercises.

It is suitable for students who want to move from conceptual understanding to implementation-oriented practice in Generative AI.

## Features

- **Structured Unit 1 content** summarizing core Generative AI principles.
- **Notebook-driven workflow** for interactive coding, experimentation, and documentation.
- **Coverage of NLP essentials** such as tokenization, embeddings, POS tagging, and NER.
- **LLM-focused orientation** including architecture concepts and model ecosystem context.
- **Project-ready setup** that can be extended for assignments, mini-projects, or demos.

## How to Install

### 1) Clone the repository

```bash
git clone <your-repo-url>
cd GENAI-PES2UG23CS629_HandsOn_1_Unit1
```

### 2) (Recommended) Create a virtual environment

```bash
python -m venv .venv
source .venv/bin/activate   # On Windows: .venv\Scripts\activate
```

### 3) Install Jupyter and common data/ML packages

```bash
pip install --upgrade pip
pip install jupyterlab notebook numpy pandas matplotlib scikit-learn
```

> If your notebooks use additional libraries (e.g., `transformers`, `torch`, `langchain`), install them as needed.

## How to Run

### Option A: Jupyter Notebook

```bash
jupyter notebook
```

Open either notebook:
- `PES2UG23CS629_HandsOn_1_Unit1.ipynb`
- `PES2U2G23CS629_Project.ipynb`

### Option B: JupyterLab

```bash
jupyter lab
```

Then navigate to the notebooks from the left sidebar and run cells in order.

## Example Usage

Typical workflow:

1. Launch Jupyter.
2. Open `PES2UG23CS629_HandsOn_1_Unit1.ipynb`.
3. Execute cells sequentially to review concepts and run practical examples.
4. Use `unit 1.txt` as a reference for theory while implementing or validating outputs.
5. Extend `PES2U2G23CS629_Project.ipynb` with your own experiments (e.g., simple NLP classification tasks).
