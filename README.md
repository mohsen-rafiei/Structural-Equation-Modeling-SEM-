
# SEM Data Analysis Project

This project demonstrates how to analyze Structural Equation Modeling (SEM) data using R and R Markdown. It includes a dataset with observed indicators for latent variables and a corresponding R Markdown file for analysis.

---

## What’s Included

1. **`sem_data.csv`**  
   - A realistic dataset for SEM analysis.
   - Includes observed indicators for two latent variables (*Cognitive Load* and *Performance*) and additional variables (*Stress*, *Age*, and *Gender*).

2. **`sem_analysis.Rmd`**  
   - An R Markdown file for SEM analysis.
   - Covers:
     - Data exploration and visualization.
     - Data preparation for SEM.
     - Building and running an SEM model using the `lavaan` package.
     - Interpreting results, including fit measures and standardized estimates.

---

## How to Use

1. **Clone this repository**:  
   Download the files to your computer.  
   ```bash
   git clone https://github.com/your-repo/SEM-Analysis.git
   cd SEM-Analysis
   ```

2. **Open the R Markdown file**:  
   Use RStudio or any R environment to open `sem_analysis.Rmd`.

3. **Install Required Packages**:  
   Ensure you have the necessary R libraries installed:  
   ```R
   install.packages(c("tidyverse", "lavaan"))
   ```

4. **Run the Analysis**:  
   - Knit the `.Rmd` file to generate an HTML report.  
   - Follow the steps in the R Markdown file to explore the data, build the SEM model, and interpret the results.

---

## Dataset Details

- **Latent Variables**:  
  - *Cognitive Load*: Measured using `Cognitive_Load_1`, `Cognitive_Load_2`, `Cognitive_Load_3`.  
  - *Performance*: Measured using `Performance_1`, `Performance_2`, `Performance_3`.  

- **Additional Variables**:  
  - *Stress*: Self-reported stress level.  
  - *Age*: Participant's age.  
  - *Gender*: Participant's gender (Male, Female, Non-Binary).  

---

## Purpose

This project provides a lightweight framework for SEM analysis, making it easy to adapt to your own research. It’s suitable for beginners and researchers looking to quickly get started with SEM in R.

---

## Contributing

Have suggestions or found a bug? Feel free to open an issue or submit a pull request. Contributions are welcome!

---

## License

This project is open-source under the [MIT License](LICENSE). You’re free to use, modify, and share it, just give credit where it’s due.

