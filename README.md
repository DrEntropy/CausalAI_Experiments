# CausalAI_Experiments

This repository supports experimentation with "Causal AI" as I work through the Causal AI book and course [Causal AI](https://altdeep.ai).

## Quick Start

### Prerequisites
- [Anaconda](https://www.anaconda.com/download) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html) installed

### Environment Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/DrEntropy/CausalAI_Experiments.git
   cd CausalAI_Experiments
   ```

2. **Create the conda environment:**
   ```bash
   conda env create -f environment.yml
   ```

3. **Activate the environment:**
   ```bash
   conda activate causal-ai-experiments
   ```

4. **Launch Jupyter Lab:**
   ```bash
   jupyter lab
   ```

### Key Packages Included

- **pgmpy**: Probabilistic Graphical Models in Python for Bayesian Networks
- **DoWhy**: A Python library for causal inference that supports explicit modeling and testing of causal assumptions
- **Jupyter**: Interactive notebook environment for experimentation
- **Standard data science stack**: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn
- **Visualization tools**: Plotly, Graphviz for causal graph visualization
- **NetworkX**: For graph analysis and manipulation
 