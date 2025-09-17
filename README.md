# Investigating the Pareto Principle in Student Software Engineering Team Projects

📄 Companion code and anonymized dataset for the paper:

> **Aditi More, Kevin Buffardi**  
> *Investigating the Pareto Principle in Student Software Engineering Team Projects*  
> Proceedings of the **Hawaii International Conference on System Sciences (HICSS-59)**, 2025  

---

## 📖 Abstract
The **Pareto principle (80/20 rule)** has been widely observed in professional and open-source software projects, where ~20% of contributors account for ~80% of outcomes.

This study investigates whether that principle applies to **student software engineering teams**. Using GitHub activity data from **94 teams (465 students)** across ten semesters, we analyzed contribution inequality with the **Hoover index** and **Lorenz curve**.

**Key findings:**
- Only **6 of 94 teams (6.4%)** matched the 80/20 Pareto distribution.  
- Most teams showed **more balanced contribution patterns**.  
- Academic factors (grading incentives, peer review, team scaffolding) likely mitigated contribution inequality.  
- Inferential statistics (Mann–Whitney U, Spearman correlation) confirmed significant differences between Pareto and non-Pareto groups.  

---

## 🚀 Reproducibility

<details>
<summary>Click to view instructions</summary>

### Requirements
```bash
pip install pandas numpy matplotlib seaborn scipy 
```
Steps

1. Clone this repository:
```bash
git clone https://github.com/aaditi2/ParetoPrincipleChronicle.git
cd pareto-analysis
```
2. Open Pareto.ipynb in Jupyter Notebook or VS Code or Colab.

3. If you are using Colab, ensure data is uploaded.

4. Run all cells in the notebook to reproduce the results.

</details>

---

##  Authors  


- **Aditi More** – California State University, Chico – [anmore@csuchico.edu](mailto:anmore@csuchico.edu)  
- **Kevin Buffardi** – California State University, Chico – [kbuffardi@csuchico.edu](mailto:kbuffardi@csuchico.edu)  


