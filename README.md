# Impact of Comorbidities on Treatment Outcomes in Tuberculosis Patients: A Biostatistical Analysis

This repository contains the full report and supplementary resources for a biostatistics research project analyzing how various comorbidities impact tuberculosis (TB) treatment outcomes in India. The study leverages survival analysis and competing risk theory, focusing on data from the **TB India Report 2022**, and was conducted under the academic guidance of Dr. Manoj Kumar Varshney, Associate Professor, Department of Statistics, Hindu College, University of Delhi.

---

## Objective

The primary aim of the study is to examine how specific comorbidities — including **HIV infection**, **COVID-19**, **diabetes mellitus**, **alcoholism**, and **tobacco use** — influence treatment outcomes such as **cure rate**, **success rate**, **death rate**, **treatment failure**, and **follow-up loss** among TB patients in India.

---

## Data Source

- **Report Used**: TB India Report 2022
- **Origin**: Ministry of Health & Family Welfare, Government of India
- **Coverage**: State-wise data on TB patient outcomes and comorbidities
- **Scope**: Patients with TB, TB-HIV co-infection, and pediatric TB

---

## Methodology

### Key Biostatistical Techniques Used:
- **Survival Analysis**: To estimate survival probabilities using Survival Function *S(t)*, Death Density Function *f(t)*, Hazard Function *λ(t)*, and Actuarial Estimation.
- **Paired t-Tests**: To test for significant differences in success and death rates between TB-only and TB-HIV patient groups.
- **Competing Risk Theory**: Used implicitly in analyzing multiple adverse outcomes (e.g., death, treatment failure).

### Key Metrics Calculated:
- **Cure Rate**  
- **Success Rate**  
- **Death Rate**  
- **% Lost to Follow-Up**  
- **Treatment Failure Rate**  
- **% Regimen Change**  
- **% Not Evaluated**

All calculations were performed using both **manual actuarial methods** and software like **SPSS** and **Microsoft Excel**.

---

##  Statistical Analysis

- **Survival Tables**: Built for TB, TB-HIV, and pediatric TB populations.
- **Actuarial Formulae Used**:
  - S(t) = Number surviving beyond time t / Total initial population
  - f(t) = Number of deaths in interval / (Total population × interval width)
  - λ(t) = f(t) / S(t)
- **Paired t-Test Results**:
  - **Success Rate Comparison**:
    - TB: **83.31%**
    - TB-HIV: **67.64%**
    - p-value: **0.000** → Significant difference
  - **Death Rate Comparison**:
    - TB: **4.56%**
    - TB-HIV: **14.75%**
    - p-value: **0.000** → Significant difference

---

##  Key Findings

### 1. **TB Survival Trends (2013–2023)**:
- TB cases declined from **2.9 million (2013)** to **1.75 million (2023)**
- TB-related deaths dropped from **515,000** to **331,000**
- Survival function has improved; hazard and death density functions have decreased

### 2. **Demographic Analysis**:
- States with the highest number of TB patients: **Uttar Pradesh**, **Maharashtra**, **Madhya Pradesh**, **Rajasthan**
- States with highest **alcohol/tobacco use among TB patients**: **Andhra Pradesh**, **Karnataka**, **Madhya Pradesh**
- COVID-19 co-infection in TB patients is present but relatively low
- Pregnant TB patients are few but require special attention

### 3. **Treatment Outcome Comparison by Comorbidity**:
- **TB-HIV patients** show significantly lower success rates and higher death, failure, regimen change, and follow-up loss rates than TB-only patients.
- **Pediatric TB patients** generally perform better than TB-HIV patients, but worse than TB-only in some states.

---

## Visualization

- Bar charts and tables were used to display state-wise comorbidity distributions
- Line plots of survival curves generated using Excel and actuarial tables

---

## Contributors

- **Vaibhav Khare (2441)**
- Aman Singh (607)  
- Lakshya Pandey (1177)  
- Nidan Swaroop (403)  
- Sachin Paswan (2203)  
- Tanya Bhat (2201)  
- Tejas Deshmukh (266)  

**Faculty Advisor**: Dr. Manoj Kumar Varshney  
*Associate Professor, Department of Statistics, Hindu College, University of Delhi*

---

## 📚 References

- [TB India Report 2022](https://tbcindia.gov.in/)
- [NCBI TB-HIV Studies](https://www.ncbi.nlm.nih.gov)
- [Indian Express on TB Mortality](https://indianexpress.com/article/explained/explained-health/indias-tb-mortality-report-2023-explained-9023266/)
- [BMC Pulmonary Medicine TB Studies](https://bmcpulmmed.biomedcentral.com/articles/10.1186/s12890-021-01740-y)

---

## 📄 License

This research project is for academic purposes only and is not intended for clinical decision-making. All data used was publicly available through government reports.

