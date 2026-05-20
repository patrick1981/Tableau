# 📊 Tableau Analytics Portfolio

**Patrick Duff** | Technical Information Specialist  
🎓 Johns Hopkins Information Systems & Artificial Intelligence (ISAI) Graduate Candidate | MBA (UMass Boston, 3.8 GPA)

💼 [LinkedIn](https://www.linkedin.com/in/patrickduff59/) | 💻 [GitHub](https://github.com/patrick1981/tableau)

---

## About Me

Data analyst specializing in **Tableau visualization and statistical dashboards**. Expert in translating complex datasets into actionable executive dashboards across healthcare, entertainment, and operations domains.

**Seeking:** Data Analyst | Business Analytics / BI roles (Remote/Boston)

---

## Table of Contents

- [Dashboard Projects](#dashboard-projects)
- [Tableau Technical Skills](#tableau-technical-skills)

---

## Dashboard Projects

### Healthcare Mortality Analytics

**🔗 [View Dashboard](https://github.com/patrick1981/tableau/blob/main/healthcare-mortality.png)**

**Business Question:** Which hospitals and states require immediate quality improvement intervention?

**Approach & Insights:**
- Geographic heat map with diverging color scale benchmarked against **2.81% national mortality ratio**
- State-level bar chart ranked by mortality ratio; top 10 highest-risk hospitals
- **Key Findings:** Wyoming (6.01%), Colorado (4.44%), Hawaii (4.39%) show 2-3× elevated rates; Memorial Care Hospital (15.9%) flagged at 6× national average

**Tableau Techniques:** Calculated fields for mortality ratios | Geographic mapping with custom color encoding | Reference lines for benchmarks | Multi-view coordinated filtering

**Impact:** Enables targeted resource allocation for quality improvement initiatives

---

### Visitor Pattern Analysis - 18-Year Time Series

**🔗 [View Dashboard](https://github.com/patrick1981/tableau/blob/main/tourist-patterns.png)**

**Business Question:** How do temperature and temporal patterns affect facility utilization?

**Approach & Insights:**
- Polynomial regression scatter plot (temperature vs. visitors) with R² annotation; box plots by day-of-week; time-series bar chart (2008-2025)
- **Key Findings:** Peak attendance at **50-58°F (800+ visitors)**; Monday 73% higher than Wednesday; 2020 COVID drop with recovery by 2022
- **Statistical Validation:** R² = 0.85 confirms strong temperature-attendance correlation

**Tableau Techniques:** Polynomial trend lines with statistical annotations | Box plots with quartiles and outlier identification | Time-series with color-coded years | Multi-dimensional filtering

**Impact:** Weather-based capacity planning and staffing optimization

---

### Airline Operational Analytics

**🔗 [View Dashboard](https://github.com/patrick1981/tableau/blob/main/airline-delays-by-carrier.png)**

**Business Question:** Which carriers and routes show critical operational delay patterns?

**Approach & Insights:**
- Pie chart (market share); horizontal bar chart (median delays); geographic heat map (delays by origin)
- **Key Findings:** Southwest dominates (39.63% market share); Continental (1,200+ min) and Delta (1,150+ min) show worst performance; hub cities concentrate delays

**Tableau Techniques:** Pie charts with market share calculations | Comparative bar charts | Geographic mapping with graduated symbols | Dashboard actions linking views

**Impact:** Identifies underperforming carriers and geographic bottlenecks

---

### Entertainment Industry Analytics - Best Picture Deep Dive

**🔗 [Oscar Zone Dashboard](https://github.com/patrick1981/tableau/blob/main/oscar-zone.png)** | **🔗 [Studio Strategies Dashboard](https://github.com/patrick1981/tableau/blob/main/studio-strategies.png)**

**Business Question:** What statistical patterns differentiate Best Picture winners from nominees?

**Approach & Insights:**
- Regression scatter plot (IMDB rating vs. vote count) with R² (0.49), p-value (<0.0001)
- Comparative box plots (winners vs. nominees); distribution histogram; studio market share heat map
- **Key Findings:** Winners have lower median rating (7.3 vs 6.8) but tighter variance; 723K votes threshold; Searchlight (8) and Columbia (6) lead nominations

**Tableau Techniques:** Linear regression with statistical annotations | Box plots with IQR and outlier identification | Histograms with reference lines | Heat maps with color intensity scaling

**Impact:** Informs Oscar campaign strategy and predicts future contenders

---

### Quality & Engagement Analytics

**🔗 [View Dashboard](https://github.com/patrick1981/tableau/blob/main/quality-engagement.png)**

**Business Question:** How do organizations optimize the quality-engagement relationship?

**Approach & Insights:**
- Scatter plot with trend analysis identifying performance clusters and outliers
- Correlation patterns enable targeted interventions

**Tableau Techniques:** Scatter plots with correlation trend lines | Color encoding for segmentation | Reference lines for benchmarking | Quadrant analysis

**Impact:** Evidence-based quality improvement and resource allocation

---

## Tableau Technical Skills

**Visualization Types:** Geographic heat maps | Regression scatter plots | Box plots | Histograms | Time-series charts | Pie charts | Heat maps | Multi-view dashboards

**Advanced Features:** Calculated fields (R², p-value, IQR, quartiles) | Trend lines (linear/polynomial) | Reference lines | Diverging color palettes | Dashboard actions | Parameters | Interactive filters

**Statistical Methods:** Regression analysis | Hypothesis testing | Distribution analysis | Benchmarking | Time-series decomposition

**Design Principles:** Executive-focused clarity | Purposeful color encoding | Logical flow (overview → detail) | Intuitive interactivity

**Domains:** Healthcare | Entertainment | Transportation | Tourism | Operations

---


*All visualizations created using Tableau Cloud. Data sources include publicly available datasets (IMDB, Academy Awards, healthcare quality databases, transportation data).*

**Last Updated:** May 2026 | ⭐ Star this repo if you found it helpful!
