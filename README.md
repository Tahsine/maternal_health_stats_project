# Maternal Health & Family Planning Analysis Project

This project conducts a statistical analysis on maternal health and family planning (PF) data from Benin and Senegal. It tests two primary hypotheses related to healthcare access and patient satisfaction.

## 📊 Hypotheses Analyzed

- **H1: Distance and Consultations**: Investigating if greater distance to health centers reduces the number of prenatal consultations. (**Confirmed**)
- **H2: Instruction level and Satisfaction**: Checking if higher education levels correlate with lower satisfaction due to higher expectations. (**Not Confirmed**)

## 📁 Project Structure

- `maternal_health_analysis.ipynb`: The main Jupyter Notebook containing the full analysis, pedagogical justifications, and formal statistical tests.
- `etrilabs_sante_maternelle_pf.csv`: The dataset used for the analysis.
- `venv/`: (Optional) Python virtual environment for local execution.

## 🚀 Getting Started

### Prerequisites

You will need Python 3.8+ and the following libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scipy`

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd maternal_health_stats_project
   ```
2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   # Windows
   .\venv\Scripts\activate
   # Unix/macOS
   source venv/bin/activate
   ```
3. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scipy
   ```

## 📝 Analysis Highlights

- **Data Cleaning**: Detailed justifications for using listwise deletion vs. imputation to maintain scientific rigor.
- **Statistical Tests**: Usage of Pearson correlation for H1 and Kruskal-Wallis (non-parametric ANOVA) for H2.
- **Formal Notation**: Inclusion of Null ($H_0$) and Alternative ($H_1$) hypotheses in mathematical form.

## 🤝 Contribution

Feel free to fork this project and submit pull requests for any analytical improvements or further visualizations.
