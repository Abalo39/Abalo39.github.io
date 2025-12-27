---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div class="cv-download-links">
  <a href="{{ base_path }}/files/cv.pdf" class="btn btn--primary"><i class="fas fa-download"></i> Download Full CV (PDF)</a>
</div>

## Research Interests
* **Robust Machine Learning:** Developing loss functions resilient to noisy data and outliers.
* **Deep Learning:** Time series forecasting, LSTM architectures, and model generalization.
* **Natural Language Processing:** Large Language Models (LLMs) and Speech Processing.
* **Explainable AI (XAI):** Interpretability in predictive modeling.

## Education
* **M.Sc. in Artificial Intelligence for Science** | African Institute for Mathematical Sciences (AIMS), South Africa | *Sept 2025 – Present*
  * **Google DeepMind Scholar**
* **Joint M.Sc. in Mathematics (Statistics Option)** | PAUSTI, Kenya & Jomo Kenyatta University of Agriculture and Technology | *Apr 2023 – Jun 2025*
  * Thesis: *A Hybrid Minkowski-Log-Cosh loss function for Robust LSTM-based time series forecasting*
  * African Union Scholar
* **B.Sc. in Mathematics, Statistics and Socio-economic Applications** | Université de Kara, Togo | *Nov 2018 – July 2021*
  * Thesis: *Evaluating the Effects of Online Learning on the Student Population of the Université de Kara During the COVID-19 Pandemic*

## Peer-Reviewed Publications
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
* **Simsoba, K.-A.**, Oscar, N., & Mageto, T. (2025). "A Hybrid Minkowski-Log-Cosh Loss Function for Robust Long Short-Term Memory-Based Time Series Forecasting." *IEEE Access*, 13, 187307–187319.

## Research Experience
* **Graduate Research Project | PAUSTI** | *2024–2025*
  * Developed a novel hybrid loss function to enhance LSTM robustness against outliers.
  * Applied models to a 10-year malaria incidence dataset (2013–2023).
* **Undergraduate Research Project | Université de Kara** | *2021–2022*
  * Designed ANN models for agricultural yield prediction.
  * Conducted feature sensitivity analysis for climate and soil variables.

## Teaching Experience
* **Mathematics and Physics Teacher | Kara, Togo** | *2019–2023*
  * Taught advanced topics including Probability, Complex Numbers, Kinematics, and Thermodynamics.
* **Volunteer Tutor | École Polytechnique de Lomé, Togo** | *2023*
  * Instructed Big Data Master’s students in Inferential Statistics and Optimization (KKT Conditions, Gradient-Based methods).

## Technical Skills
* **Programming:** Python (Advanced), R, MATLAB, SQL, C/C++
* **Frameworks:** TensorFlow, PyTorch, Scikit-learn, Pandas, NumPy
* **Data Tools:** Power BI, STATA, SPSS, GIS, MySQL
* **Research:** LaTeX, GitHub, Google Colab, Overleaf

## Awards & Honors
* **Google DeepMind Scholarship** (2025–2026)
* **African Union Scholarship** (2023–2025)
* **Togolese National Government Scholarship** (2015–2018)
