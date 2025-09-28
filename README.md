# Portfolio Optimization Using Genetic Algorithm

This project demonstrates how Genetic Algorithms (GA) can be applied to portfolio optimization in finance.  
It explores asset selection, weight optimization, and risk-return trade-offs to build efficient investment portfolios.

---

## 📂 Project Structure
- `CodeFile.Rmd` → R Markdown source code
- `final-report.pdf` → Detailed written report
- `README.md` → Overview and outputs
- `figs/` → Generated plots (added after running code)

---

## ⚙️ Methodology
1. **Data Setup**: Returns and risks assigned to 10+ assets (tech, finance, and diversified companies).
2. **Fitness Function**: Maximizes return-to-risk ratio.
3. **Genetic Algorithm**:
   - Population size = 100  
   - Max iterations = 200  
   - Mutation rate = 0.2  
4. **Evaluation**: Compared optimized, random, and equally weighted portfolios.
5. **Extended Model**: Introduced trade-off parameter *alpha (α)* to balance risk vs. return.

---

## 📊 Sample Results

**Optimized Portfolio Weights**

| Asset                   | Weight  |
|--------------------------|---------|
| Apple                   | 0.24    |
| Microsoft               | 0.20    |
| Amazon                  | 0.18    |
| Reliance Industries     | 0.15    |
| Tata Consultancy Services | 0.08 |
| HDFC Bank               | 0.04    |
| Alphabet                | 0.05    |
| Infosys                 | 0.03    |
| Facebook                | 0.02    |
| ICICI Bank              | 0.01    |

**Performance Metrics**
- **Return**: 0.1709  
- **Risk**: 0.1620  

---

## 📈 Example Plot

![Risk vs Return](figs/risk_return_plot.png)

*(You can generate this plot by running the R Markdown file and saving figures in the `figs/` folder.)*

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/Version1Venky/Portfolio-Optimization-.git
