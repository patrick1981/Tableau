# Tableau Analytics Portfolio
**Patrick Duff** | Data Analyst  
U.S. Navy Veteran | Johns Hopkins AI Graduate Candidate

Portfolio: [github.com/patrick1981/tableau](https://github.com/patrick1981/tableau)

---

## About This Portfolio

This repository showcases data analytics projects built using Tableau, demonstrating expertise in data visualization, statistical analysis, and business intelligence across multiple domains including healthcare, operations, transportation, and entertainment. Each dashboard translates complex datasets into actionable insights for stakeholder decision-making.

**Technical Capabilities Demonstrated:**
- Advanced statistical visualization (regression analysis, hypothesis testing, distribution analysis, box plots with quartiles)
- Geographic data mapping and spatial analysis
- Time-series analysis and trend modeling
- Multi-dimensional categorical analysis
- Comparative analytics and benchmarking
- Interactive dashboard design with calculated fields, reference lines, and statistical annotations

---

## Projects

### 1. Healthcare Mortality Analytics
![Healthcare Mortality Dashboard](./healthcare-mortality-dashboard.png)

**Business Question:** Which hospitals and states show concerning mortality patterns requiring quality improvement intervention?

**Analysis Approach:**
- Analyzed hospital mortality rates across 50+ U.S. states and individual facilities
- Applied geographic visualization to identify regional performance clusters
- Developed comparative benchmarking against national average (2.81% mortality ratio)
- Created color-coded ranking system for rapid identification of performance outliers

**Key Insights:**
- **Geographic patterns:** Identified states exceeding national mortality benchmarks with clear regional concentration
- **Facility-level targeting:** Ranked hospitals by mortality performance to prioritize quality improvement resources
- **Performance distribution:** Revealed wide variance between top and bottom performing facilities, suggesting systemic rather than random factors
- **Actionable visualization:** Color-coded map enables healthcare administrators to rapidly identify intervention priorities

**Skills Demonstrated:** Healthcare quality metrics, geographic data visualization, statistical benchmarking, comparative performance analysis, executive dashboard design

**Business Impact:** Enables data-driven resource allocation for quality improvement initiatives by identifying highest-need facilities and regions

---

### 2. Visitor Pattern Analysis - 18-Year Time Series (2008-2025)
![Visitor Patterns Dashboard](./visitor-patterns-dashboard.png)

**Business Question:** How do environmental factors and temporal patterns affect facility utilization over an 18-year period?

**Analysis Approach:**
- Analyzed 18 years of visitor data (2008-2025) using statistical methods including polynomial regression analysis, box plots, and trend modeling
- Applied regression to model temperature-visitor correlation and identify optimal operational conditions
- Examined day-of-week variance using statistical comparison methods
- Identified long-term trends including COVID-19 impact (2020) and recovery trajectory

**Key Insights:**
- **Optimal temperature range:** 50-58°F drives peak attendance (800+ visitors), with clear decline outside this range
- **Day-of-week variance:** Monday visitation 73% higher than Wednesday, with consistent weekly patterns suggesting staffing optimization opportunities
- **Statistical validation:** Mean and median metrics nearly identical across multiple years, indicating normal distribution and predictable operational trends
- **Long-term patterns:** Clear 2020 COVID impact with visible recovery trajectory; facility returned to pre-pandemic patterns by 2022
- **Environmental correlation:** Strong relationship between temperature and attendance visible through regression curve, enabling predictive capacity planning

**Skills Demonstrated:** Time-series analysis, polynomial regression modeling, statistical distribution analysis, pattern recognition, environmental correlation analysis, box plot visualization, long-term trend identification

**Business Impact:** Informs staffing decisions based on day-of-week patterns; enables capacity planning based on weather forecasts; provides historical context for budgeting and resource allocation

---

### 3. Airline Operational Analytics
![Airline Delay Dashboard](./airline-delays-dashboard.png)

**Business Question:** Which carriers and routes show the most significant operational delay patterns?

**Analysis Approach:**
- Analyzed flight delay data across 10+ major U.S. carriers
- Created multi-dimensional views examining market share, median delays, and geographic distribution
- Implemented interactive filtering for stakeholder exploration of specific carriers and time periods
- Applied comparative analysis to identify performance variance across carriers and routes

**Key Insights:**
- **Market concentration:** Southwest handles 39.6% of tracked flights, demonstrating dominant market position with operational scale advantages
- **Performance variance:** Continental and Delta show highest median delays (1,200+ minutes), suggesting operational efficiency challenges
- **Geographic patterns:** Hub-specific delay concentrations visible through state-level mapping, revealing infrastructure bottlenecks
- **Operational targeting:** Visualization enables rapid identification of underperforming routes and carriers for process improvement initiatives
- **Competitive landscape:** Clear performance differentiation across carriers suggests operational best practices are not uniformly adopted

**Skills Demonstrated:** Operational analytics, market share analysis, comparative performance metrics, geographic visualization, transportation KPIs, pie chart and bar chart design for categorical data

**Business Impact:** Enables airlines to benchmark performance against competitors; identifies geographic regions requiring infrastructure investment; informs route planning and operational improvement initiatives

---

### 4. Entertainment Industry Analytics - Best Picture Overview
![Best Picture Dashboard](./best-picture-dashboard.png)

**Business Question:** What patterns exist among Academy Award Best Picture films regarding studios, talent, and audience reception?

**Analysis Approach:**
- Analyzed Academy Award Best Picture nominees and winners across multiple decades
- Examined production company success rates and market concentration
- Identified top talent (actors) with most nominations and wins to reveal Academy preferences
- Assessed IMDB rating distribution to understand alignment between critical (Academy) and audience reception

**Key Insights:**
- **Studio dominance:** Columbia Pictures leads with 10 nominations, indicating consistent quality output and strong Oscar campaign capabilities
- **Talent concentration:** Tom Hanks, Jesse Plemons, and Leonardo DiCaprio each have 6 nominations, suggesting these actors appear in Academy-preferred film types
- **Rating distribution:** Most Best Picture films cluster between 7.6-8.0 IMDB rating, establishing clear quality threshold
- **Statistical validation:** Normal distribution pattern (mean ≈ median ≈ 7.8) suggests Academy selections align with broad audience preferences rather than critics-only perspective
- **Win rate analysis:** Some actors/studios have high nomination counts but low win rates, suggesting factors beyond quality (timing, competition, campaign strength) influence outcomes

**Skills Demonstrated:** Categorical analysis, distribution analysis with histograms, entertainment industry metrics, talent analytics, production company analysis, multi-view dashboard design

**Business Impact:** Informs Oscar campaign strategies by identifying historical patterns in Academy preferences; helps studios understand competitive landscape; provides talent agents data on actors' Oscar track records

---

### 5. Entertainment Industry Analytics - Best Picture Deep Dive (Advanced Statistical Analysis)
![Best Picture Expanded Dashboard](./best-picture-expanded-dashboard.png)

**Business Question:** How do studio market dynamics, critical reception, and audience engagement patterns differ between Best Picture winners and nominees, and what statistical relationships exist between these variables?

**Analysis Approach:**
- Analyzed 13 years of Academy Award Best Picture data (2010-2022) across four complementary visualizations
- Created heat map visualizing studio market share evolution with 20+ production companies tracked longitudinally
- Applied box plot statistical visualization with explicit quartile ranges, medians, and outlier identification to compare rating distributions between winners and nominees
- Developed scatter plot with linear regression including R-squared (0.490157), standard error (0.287369), and p-value significance testing (p < 0.0001)
- Constructed histogram with mean and median reference lines to assess overall rating distribution shape

**Key Statistical Insights:**

**Distribution Analysis (Box Plot):**
- **Winners' rating distribution:** Tight range (7.3-8.2 IQR) with median 7.300, indicating Academy consistently selects films within narrow quality band
- **Nominees' rating distribution:** Wider range (6.8-8.8) with median 6.800, suggesting nominations cast broader net but with more variance
- **Counterintuitive finding:** Winners' median LOWER than nominees' median, challenging assumption that Academy selects highest-rated films; instead suggests preference for "safe" consistently-rated films over polarizing high-rated ones
- **Outlier analysis:** Few outliers beyond whiskers in both groups, indicating most films cluster within expected ranges
- **Overall average:** 7.664 serves as baseline for "Best Picture quality" threshold

**Correlation Analysis (Scatter Plot with Regression):**
- **Moderate positive correlation (R² = 0.490157):** 49% of rating variance explained by vote volume, indicating audience engagement and critical quality are moderately related but not deterministic
- **Statistical significance (p < 0.0001):** Relationship between audience engagement (number of votes) and rating is highly statistically significant, not due to random chance
- **Standard error = 0.287369:** Model prediction accuracy within ~0.3 rating points, indicating reasonable predictive reliability
- **Winner engagement ceiling:** 723,418 votes represents upper boundary annotation for winner-level films, suggesting diminishing returns on engagement beyond this threshold
- **Median IMDB rating reference line:** 7.700 horizontal line shows most films cluster near this value regardless of vote volume

**Market Dynamics (Heat Map & Bar Chart):**
- **Studio concentration:** Warner Bros. leads with 10 nominations, followed by Searchlight Pictures (8) and Columbia (6)
- **Competitive landscape:** 20+ studios represented with no single monopoly; market is distributed across major studios and independent production companies
- **Win rate variance:** Some smaller studios (A24, Participant) have higher win-to-nomination ratios than major studios, suggesting Academy values independent cinema diversity
- **Temporal patterns:** Heat map reveals studio dominance shifts over time; traditional studios (Warner, Columbia, Paramount) maintain consistent presence while new entrants (Amazon Studios, A24) gain traction post-2015
- **Market entry barriers:** New studios can achieve Best Picture nominations relatively quickly (Amazon's first nomination within 2 years of film production launch)

**Distribution Shape (Histogram):**
- **Mean vs. Median:** Mean title rating (22) slightly lower than median (25), indicating slight left skew in overall film count distribution
- **Normal-ish distribution:** Overall shape approximates normal distribution with most films clustering around 7.6-7.8 rating range
- **Quality floor:** Very few films below 7.0 receive nominations, establishing de facto Academy quality threshold

**Tools:** Tableau (heat maps with temporal dimensions, box plots with quartiles and outliers, scatter plots with regression statistics and significance testing, histograms with statistical reference lines, calculated fields for R², p-value, standard error)

**Skills Demonstrated:** 
- Advanced statistical visualization (quartiles, IQR, outliers, distribution shape analysis)
- Regression analysis with goodness-of-fit metrics (R², standard error, p-value interpretation)
- Hypothesis testing and statistical significance assessment
- Comparative distribution analysis between two groups
- Temporal market share analysis with heat maps
- Multi-view dashboard design synthesizing four analytical perspectives into cohesive narrative
- Statistical literacy: translating technical metrics (R², p-value, standard error) into business insights
- Annotation strategy: using reference lines and text to guide viewer interpretation

**Business Impact & Strategic Implications:** 

The counterintuitive finding that winners have LOWER median ratings than nominees (7.3 vs 6.8) combined with tighter variance suggests Academy voting behavior prioritizes consensus "safe" choices over potentially divisive but high-rated films. 

**Oscar Campaign Strategy Implications:**
- Studios should focus on broad appeal (minimizing negative reactions) rather than maximizing critical praise
- Films with polarizing elements (even if highly rated by supporters) face Academy disadvantage
- Consistent quality across all voter segments matters more than peak excellence

**Engagement Strategy Insights:**
The moderate R² (0.49) in engagement-rating correlation indicates factors beyond quality drive audience engagement—suggesting marketing spend, star power, release timing, and social media campaigns play roles nearly equal to film quality in determining visibility. Winner engagement ceiling at 723K votes suggests diminishing returns on marketing beyond this threshold.

**Market Entry Strategy:**
Heat map temporal analysis shows new entrants (Amazon, A24) successfully competing with established studios, suggesting Academy actively diversifies nominations to include independent cinema. This creates opportunities for emerging studios to compete without decades-long industry presence.

**Statistical Rigor Note:** 
P-value < 0.0001 confirms observed patterns are not due to random chance, providing confidence for predictive modeling of future Academy selections based on these metrics. Standard error of 0.287 indicates predictions within acceptable business decision-making tolerance.

---

## Technical Skills Demonstrated Across Portfolio

**Data Visualization Techniques:**
- Geographic mapping and spatial analysis with custom color schemes
- Time-series visualization with trend lines and seasonal patterns
- Advanced statistical charts (box plots with quartiles/outliers, histograms with reference lines, scatter plots with regression)
- Heat maps for temporal and categorical data visualization
- Comparative bar charts and rankings with multiple dimensions
- Multi-view dashboards with coordinated filtering and navigation
- Strategic use of annotations and reference lines to guide interpretation

**Analytical Methods:**
- Regression analysis and correlation modeling (linear regression, polynomial regression, R² calculation)
- Statistical hypothesis testing and significance assessment (p-value interpretation)
- Distribution analysis (normal distribution, variance, quartiles, IQR, outliers, skewness)
- Benchmarking and comparative performance analysis
- Pattern recognition and anomaly detection
- Time-series decomposition and trend analysis
- Market concentration and share analysis

**Statistical Metrics Applied:**
- Mean, median, mode
- Standard deviation and standard error
- Interquartile range (IQR)
- R-squared (coefficient of determination)
- P-value (statistical significance)
- Quartiles (Q1, Q2/median, Q3)
- Outlier identification (beyond 1.5 × IQR)

**Business Domains:**
- Healthcare operations and quality metrics
- Transportation and logistics analytics
- Entertainment industry and media metrics
- Operational efficiency and resource optimization
- Market dynamics and competitive analysis
- Facility management and capacity planning

**Tableau Features:**
- Calculated fields and custom metrics (statistical calculations, aggregations)
- Interactive filters and parameters for user exploration
- Geographic mapping with custom territories and color encoding
- Statistical reference lines (average, median, quartiles, regression)
- Trend lines with statistical annotations (R², p-value, standard error)
- Color encoding for categorical and continuous data
- Dashboard design for executive audiences with minimal technical background
- Annotations and tooltips for contextual information

---

## About Me

Data analyst with 7+ years of experience transforming complex datasets into actionable business intelligence. Currently pursuing MS in Information Systems & Artificial Intelligence at Johns Hopkins University - Carey Business School (Expected 2028). Completed MBA from University of Massachusetts Boston (2026, GPA: 3.77) and MS in Library and Information Science from Simmons University (2016, GPA: 3.75). 

Proven expertise building production ETL pipelines ($65,000 in annual cost savings), designing SQL databases, and creating executive dashboards that drive operational decisions. U.S. Navy veteran with demonstrated ability to perform systematic analysis under pressure in mission-critical environments.

**Professional Achievements:**
- Architected production Python ETL pipeline automating 6-week manual process into <2-hour workflow
- Conducted root cause analysis on department-level system outages using data-driven debugging
- Created data visualizations and infographics for executive-level annual reporting
- Recipient of Outstanding Performance Bonuses (FY2022-2025) for sustained analytical excellence

**Technical Proficiencies:**  
Python (Pandas, Openpyxl) | SQL (queries, database design) | Tableau (dashboards, statistical visualization, calculated fields) | Excel (PivotTables, Power Query, VLOOKUP) | Statistical Analysis (regression, hypothesis testing, distribution analysis) | ETL Pipeline Development | Database Design (RDBMS, ERD modeling, BCNF normalization) | Healthcare Analytics

**Education:**
- **Johns Hopkins University - Carey Business School** | MS in Information Systems & Artificial Intelligence | Expected 2028
- **University of Massachusetts Boston** | MBA | Completed 2026 | GPA: 3.77
- **Simmons University** | MS in Library and Information Science | Completed 2016 | GPA: 3.75

---

## Portfolio Use Cases

This portfolio demonstrates capabilities relevant to:

**Data Analyst Roles:**
- Translating business questions into analytical frameworks
- Conducting exploratory data analysis to identify patterns
- Creating visualizations that communicate insights to non-technical stakeholders
- Applying statistical methods to validate findings

**Business Intelligence Analyst Roles:**
- Designing executive dashboards for strategic decision-making
- Benchmarking performance across multiple dimensions
- Identifying operational inefficiencies through data analysis
- Building repeatable analytical frameworks

**Healthcare Analytics Roles:**
- Understanding healthcare quality metrics and benchmarking
- Visualizing clinical and operational data for improvement initiatives
- Applying statistical methods to healthcare datasets

**Market Research & Strategy Roles:**
- Analyzing competitive landscapes and market dynamics
- Identifying trends in consumer behavior and preferences
- Translating analytical findings into strategic recommendations

---

## Contact

I'm actively seeking entry-level Data Analyst or Business Intelligence Analyst roles where I can apply analytical skills, statistical expertise, and passion for data-driven problem-solving to help organizations make better decisions.

**Open to:** Remote positions, Boston-area opportunities, healthcare analytics, business intelligence, data visualization roles
 
💼 LinkedIn: [https://www.linkedin.com/in/patrickduff59/](https://www.linkedin.com/in/patrickduff59/)
💻 GitHub: [github.com/patrick1981/Tableau](https://github.com/patrick1981/Tableau)  
🎖️ U.S. Navy Veteran (Honorable Discharge, 1999-2001)

---
---

## Acknowledgments

All visualizations created using Tableau Desktop/Public. Data sources include publicly available datasets (IMDB, Academy Awards, healthcare quality databases, transportation data) and academic project data. Dashboards demonstrate analytical capabilities and are intended for portfolio purposes to showcase technical skills and business thinking.

Statistical methods applied follow standard practices in data analysis and business intelligence. All findings and insights are based on available data within specified time periods and should be interpreted within their analytical context.

---

*Last Updated: 19 May 2026*  
**⭐ If you found this portfolio helpful or interesting, please consider starring this repository!**
