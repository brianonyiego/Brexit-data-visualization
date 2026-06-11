# Brexit Impact on UK SMEs: Data Visualization and Strategic Framework Analysis

> A Python-based data visualization and business analysis project that explores the impact of Brexit on UK Small and Medium-Sized Enterprises (SMEs) using survey data, strategic management frameworks, and interactive visualizations.

## Project Overview

This project analyzes the key challenges, concerns, and strategic responses of UK SMEs during and after Brexit. Using survey data from The HR Dept and multiple business strategy frameworks, the project creates visual representations of SME concerns, Brexit-related risks, optimism levels, and strategic adaptation mechanisms.

The analysis combines descriptive statistics, business intelligence visualization, and theoretical interpretation through frameworks such as Porter's Five Forces, Stakeholder Theory, Dynamic Capabilities, PESTEL Analysis, and the Resource-Based View (RBV).

## Objectives

- Analyze major concerns affecting UK SMEs
- Examine Brexit-specific business challenges
- Evaluate SME optimism regarding Brexit outcomes
- Visualize survey findings using charts and graphs
- Apply strategic management theories to Brexit-related business responses
- Interpret SME adaptation strategies through academic frameworks
- Demonstrate data visualization techniques using Python

## Dataset Source

The primary survey data was obtained from:

The HR Dept Annual SME Survey

Source:

https://www.hrdept.co.uk/press/brexit-skills-shortage-employee-status-top-three-concerns-uk-smes-says-hr-dept-annual-survey/

The survey highlights key issues faced by UK SMEs, including:

- Skills shortages
- Brexit uncertainty
- Employment status concerns
- Staff retention challenges
- Wage-related pressures

## Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Data analysis and visualization |
| Matplotlib | Static chart generation |
| Seaborn | Statistical data visualization |
| Plotly | Interactive visualizations |
| Pandas | Data manipulation and tabular analysis |

## Visualizations Generated

### 1. Top Concerns Affecting SMEs

This horizontal bar chart illustrates the most significant concerns reported by SMEs.

#### Variables

| Concern | Percentage (%) |
|----------|---------------|
| Skills Shortages | 37 |
| Brexit | 37 |
| Employment Status Confusion | 33 |
| Staff Retention | 29 |
| Living/Minimum Wage | 26 |

#### Visualization Type

```text
Horizontal Bar Chart
```

#### Purpose

To identify the most pressing operational and strategic challenges faced by SMEs.

---

### 2. Brexit-Specific Concerns

This chart focuses on concerns directly associated with Brexit.

#### Variables

| Concern | Percentage (%) |
|----------|---------------|
| Worried About UK Economy | 58 |
| Supplier Cost Increase | 42 |
| Access to EU Labour | 18 |
| No Brexit Concerns | 21 |

#### Visualization Type

```text
Horizontal Bar Chart
```

#### Purpose

To examine how Brexit influenced SME perceptions regarding economic performance, labor availability, and supply chain costs.

---

### 3. SME Optimism About Brexit

This visualization explores positive expectations held by SMEs regarding Brexit outcomes.

#### Variables

| Optimistic View | Percentage (%) |
|----------------|---------------|
| Employment Law Improvements | 37 |
| Reduced Regulation | 30 |
| Global Trade Opportunities | 25 |
| Positive Economic Impact | 24 |
| Not Hopeful | 32 |

#### Visualization Type

```text
Horizontal Bar Chart
```

#### Purpose

To assess optimism and expectations among SME owners and managers.

---

### 4. Overall Brexit Outlook

A pie chart summarizing the overall sentiment of SMEs toward Brexit.

#### Categories

- Hopeful About Brexit
- Not Hopeful
- No Concerns

#### Visualization Type

```text
Pie Chart
```

#### Purpose

To provide a high-level overview of SME sentiment toward Brexit.

---

### 5. Strategic Impact Radar Chart

The radar chart evaluates Brexit's impact on SMEs through five major strategic management frameworks.

#### Frameworks

- Porter's Five Forces
- Stakeholder Theory
- Dynamic Capabilities
- PESTEL Analysis
- Resource-Based View (RBV)

#### Example Impact Scores

| Framework | Score (/10) |
|------------|------------|
| Porter's Five Forces | 8 |
| Stakeholder Theory | 7 |
| Dynamic Capabilities | 9 |
| PESTEL | 6 |
| Resource-Based View | 8 |

#### Visualization Type

```text
Radar Chart
```

#### Purpose

To compare the relative strategic importance of different theoretical frameworks in explaining SME responses to Brexit.

---

### 6. Strategic Framework Sunburst Diagram

The sunburst visualization maps strategic frameworks and their associated themes.

#### Main Frameworks

- Porter's Five Forces
- Stakeholder Theory
- Dynamic Capabilities
- PESTEL
- Resource-Based View

#### Example Themes

- Supplier Power
- Buyer Power
- Employee Relations
- Sensing
- Seizing
- Political Factors
- Economic Factors
- Internal Resources
- Capabilities
- Brand Value

#### Visualization Type

```text
Interactive Sunburst Chart
```

#### Purpose

To illustrate relationships between Brexit-related strategic concepts and business frameworks.

---

### 7. Framework Summary Table

The project generates an interactive summary table comparing major strategic frameworks.

#### Columns

- Framework
- Focus Area
- Key SME Insights

#### Visualization Type

```text
Interactive Table
```

#### Purpose

To summarize theoretical interpretations and managerial implications.

## Strategic Framework Analysis

### Porter's Five Forces

Examines:

- Supplier bargaining power
- Buyer bargaining power
- Competitive rivalry
- Threat of new entrants

Key Finding:

Brexit increased supplier costs and intensified market uncertainty for SMEs.

### Stakeholder Theory

Examines:

- Employee relationships
- Supplier relationships
- Customer engagement

Key Finding:

Local stakeholder management became increasingly important after Brexit.

### Dynamic Capabilities

Examines:

- Sensing opportunities
- Seizing opportunities
- Organizational transformation

Key Finding:

Adaptable SMEs were better positioned to respond to Brexit-related disruptions.

### PESTEL Analysis

Examines:

- Political factors
- Economic conditions
- Social impacts
- Technological developments
- Environmental considerations
- Legal implications

Key Finding:

Political and economic uncertainty significantly influenced SME decision-making.

### Resource-Based View (RBV)

Examines:

- Internal capabilities
- Competitive resources
- Strategic assets

Key Finding:

SMEs that leveraged internal strengths demonstrated greater resilience.

## Running the Project

### Install Required Libraries

```bash
pip install matplotlib
pip install seaborn
pip install plotly
pip install pandas
```

### Run the Script

```bash
python brexit_sme_analysis.py
```

### Outputs Generated

The script generates:

- SME concern bar charts
- Brexit concern visualizations
- Brexit optimism charts
- Brexit outlook pie chart
- Strategic impact radar chart
- Interactive sunburst chart
- Interactive framework summary table

## Project Structure

```text
Brexit_SME_Analysis/
│
├── brexit_sme_analysis.py
├── README.md
│
├── data/
│   └── hr_dept_survey_data
│
├── figures/
│   ├── top_concerns.png
│   ├── brexit_concerns.png
│   ├── brexit_optimism.png
│   ├── brexit_outlook.png
│   └── radar_chart.png
│
└── interactive_visualizations/
    ├── sunburst_chart.html
    └── framework_table.html
```

## Key Findings

- Skills shortages and Brexit were the most significant concerns among SMEs.
- Economic uncertainty remained a major challenge following Brexit.
- Many SMEs viewed regulatory reform and global trade opportunities positively.
- Dynamic capabilities emerged as the most influential framework for explaining successful SME adaptation.
- Organizations with strong internal resources and stakeholder relationships demonstrated greater resilience.

## Future Improvements

- Integration of additional SME datasets
- Time-series Brexit impact analysis
- Machine learning-based sentiment analysis
- Interactive dashboards using Dash or Streamlit
- Comparative analysis across industries
- Regional SME impact assessment

## Disclaimer

This project is intended for educational, research, and analytical purposes. Survey data and findings should be interpreted within the context of the original source and supporting academic literature.
