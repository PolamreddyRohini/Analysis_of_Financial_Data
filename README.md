# 📊 Analysis of Financial Data

This project demonstrates foundational statistical analysis and hypothesis testing using **R Studio**. It is aimed at equipping users with hands-on experience in data manipulation, visualization, and the application of statistical methods on real-world datasets.

---

## 📁 Project Structure

### 🔹 Modules Covered

1. **Bar Plot for DSA Component**
2. **Exploration of Cars Dataset**
3. **Preliminary R Commands & Usage**
4. **Probability Distributions**  
   - Binomial  
   - Poisson  
   - Normal  
5. **Hypothesis Testing**  
   - One-sample and Two-sample *t-tests*  
   - *Z-tests*  
   - *Chi-square* tests  
6. **Descriptive Statistics**  
   - Skewness  
   - Kurtosis  
7. **Financial Dataset (TSLA) Analysis**

---

## 📚 Dataset

### 🗂️ `cars.csv`
- **Age** – Age of individuals  
- **Gender** – Gender (0 = Female, 1 = Male)  
- **Miles** – Distance traveled  
- **Debt** – Debt amount  
- **Income** – Individual income  
- **Sales** – Revenue generated  

### 🗂️ `TSLA.csv`
Used for advanced statistical and visual analysis including:
- Summary statistics
- Histograms
- Skewness and kurtosis
- Probability distributions
- Hypothesis testing

---

## 🧪 Key Statistical Functions Used in R

| Function        | Purpose                                      |
|----------------|----------------------------------------------|
| `read.csv()` / `read_csv()` | Import CSV datasets            |
| `hist()`        | Create histograms                           |
| `t.test()`      | Perform *t-tests*                           |
| `chisq.test()`  | Chi-square test                             |
| `pnorm()` / `dnorm()` | Normal distribution functions        |
| `dbinom()` / `rbinom()` | Binomial distribution             |
| `dpois()` / `rpois()` | Poisson distribution                |
| `skewness()` / `kurtosis()` | Descriptive statistics (moments) |
| `summary()`     | Descriptive summary of dataset              |

---

## 🧠 Hypothesis Testing

### 🔹 One-Sample Z-Test
Tests whether the sample mean significantly differs from a known population mean.

### 🔹 Two-Sample Z-Test
Compares the means of two independent samples.

### 🔹 Chi-Square Test
Tests for association between categorical variables.

---

## 📊 Visualizations
- Bar plots using `barplot()`
- Histograms with custom colors and labels
- Descriptive summaries using `summary()` and `str()`

---

## 🛠️ Tools & Tech

- **Language**: R  
- **IDE**: R Studio  
- **Libraries Used**:  
  - `readr`  
  - `moments`
