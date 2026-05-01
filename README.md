
# Allegheny County from insights to action: Primary care and asthma diagnosis behavior 2016-2019. A machine learning and linear programming approach to public health resource allocation.

Analyzed 4,000+ observations of medical visit counts and asthma diagnoses among pediatric patients across nearly 400 census tracts in Allegheny County between 2016 and 2019 to identify local and temporal trends and optimize resource allocation.

Developed an end-to-end prescriptive analytics pipeline to optimize the allocation of theoretical **5,000 supplemental clinical visits** across Allegheny County. By integrating **Machine Learning (Linear Regression,Random Forest)** for predictive modeling with **Linear Programming (Pyomo & GLPK)** for resource optimization, this project identifies high-impact "hotspots" to minimize the regional asthma burden.

The resulting strategy provides a surgical-grade roadmap that prioritizes census tracts based on marginal health benefits, enabling health administrators to transition from reactive care to a data-driven, preventive intervention model.


## Steps in the project

- Data cleaning and preparation

- Exploratory Data Analysis

- Trend and pattern identification

- Visualization and dashboard creation

- Machine learning for predictive modeling.

- Linear programming for resource optimization

## Tools used

**Python:** Pandas, Numpy, Scikit-learn, RandomForestRegressor, train_test_split, mean_squared_error, r2_score, Plotly, Json, Pyomo, GLPK

**PowerBI** 

**Excel**


## Some Insights and Conclussions

- The primary care system is reaching approximately **2,000 new children every year**, indicating either increased healthcare penetration or demographic growth within Allegheny County.

- As prevention efforts increase (well-child visits), the asthma diagnosis rate has fallen by nearly **1.3 percentage points** over the four-year period.

- Consistent Primary Care growth suggests successful outreach and improved healthcare enrollment for the pediatric population, although the 2018-2019 plateau might indicate that the system is reaching a point of saturation or a stabilization in local demographics. This growth is not geographically uniform.

- More than **8 out of 10 children** consistently receive their annual well-child check-ups. But, while some neighborhoods have reached total coverage for preventive visits, others have seen their safety net collapse by nearly half.

- The healthcare strategy in Allegheny County from 2016 to 2019 has been effective in simultaneously expanding patient coverage and improving specific health outcomes.

- High linear correlation between wellness checks and asthma identification.

- The **Multiple Linear Regression** is the best model for this study.

- Assuming we are given the number of new preventive visits that can be carried out in a year, we can maximize the impact of each of these visits with the aim of minimizing the incidence of asthma. To achieve this, we must be highly selective in how these visits are distributed, paying special attention to the central-eastern area.
## Authors

- David Fernández
- https://www.linkedin.com/in/david-fern%C3%A1ndez-908b9a18b/

