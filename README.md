# 📊 Distributions_Analysis_R

Simulation and statistical analysis of random samples from classical probability distributions in **R**.  
Моделирование и статистический анализ случайных выборок из классических распределений в **R**.

---

## 📌 About / О проекте

🎓 Developed as part of a course on post-statistical methods of machine learning.  
💡 Generates samples, plots ECDF/histograms/densities, computes numerical characteristics, estimates parameters, and tests distribution fit (χ²).  
📦 Covers **discrete** (binomial, geometric) and **continuous** (exponential, gamma) distributions.

🎓 Разработано в рамках курса по статистическим методам машинного обучения.  
💡 Генерация выборок, построение ЭФР/гистограмм/плотностей, числовые характеристики, оценка параметров и проверка согласия (χ²).  
📦 Охватывает **дискретные** (биномиальное, геометрическое) и **непрерывные** (экспоненциальное, гамма-) распределения.

---

## 🔧 Features / Возможности

- 🎲 Sample generation (N ∈ [100, 200]) / Генерация выборок (N ∈ [100, 200])
- 📈 Frequency polygon, histogram, ECDF / Полигон частот, гистограмма, ЭФР
- 🧮 Mean, variance, SD, mode, median, skewness, kurtosis / Среднее, дисперсия, СКО, мода, медиана, асимметрия, эксцесс
- 📐 Theoretical vs empirical comparison / Сравнение теоретических и выборочных характеристик
- 🔎 Parameter estimation: MLE & Method of Moments / Оценка параметров: ММП и метод моментов
- ✅ Chi-squared goodness-of-fit test / Проверка согласия χ²

---

## 📁 Structure / Структура

- **Task 1 — Discrete / Дискретные**
  - Binomial (rbinom, pbinom), Geometric (rgeom, pgeom)
  - ECDF, histogram, frequency polygon
  - Numerical & theoretical characteristics
  - Parameter estimation (MLE, MM)
  - χ² goodness-of-fit

- **Task 2 — Continuous / Непрерывные**
  - Exponential (rexp, dexp, pexp), Gamma (rgamma, dgamma, pgamma)
  - Histogram with density overlay + kernel density estimate
  - Numerical & theoretical characteristics
  - Parameter estimation (MLE, MM)
  - χ² goodness-of-fit

---
