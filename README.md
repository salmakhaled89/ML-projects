# ML-projects
An advanced Machine Learning framework implementing Classification, Regression, Ensemble techniques, and Regularization across Car Price and FIFA Player datasets, including structural ERD modeling.
# Multi-Dataset Predictive ML Framework & Data Modeling

An advanced, dual-pipeline Machine Learning repository analyzing and modeling two distinct domain datasets (**Car Pricing** and **FIFA Player Performance**). This framework seamlessly integrates structural database design via **Entity-Relationship Diagrams (ERDs)**, extensive data preprocessing, and hybrid Predictive Analytics spanning both **Supervised Classification** and **Continuous Regression** modeling.

## 1. Car Price Optimization Pipeline
- **Data Preprocessing & Feature Engineering:** Cleaned, encoded, and transformed raw vehicle characteristics. Engineered a custom feature mapper, partitioning continuous pricing into a categorical target class: `Price_Category` (`Cheap`, `Moderate`, `Expensive`).
- **Classification Tasks:** Evaluated multiple standard classifiers to dynamically group vehicles into their appropriate market segment tiers based on physical specifications.
- **Regression Tasks:** Implemented Multi-variable Linear Regression to output real-time continuous market values.
- **Data Architecture:** Embedded a custom relational ERD mapping out the logical structural entities of car attributes, manufacturers, and price tiers.

## 2. FIFA Players Performance & Valuation Engine
- **Target Engineering:** Evaluated raw player attributes to construct a supervised `Performance_Tier` classification metric mapped from overall ratings ($OverAll\_Rating$). Adjusted financial evaluation by deploying target continuous metrics for market value calculation ($Value\_per\_M\$$).
- **Advanced Optimization Techniques:**
  - **Ensemble Learning:** Deployed predictive voting/stacking ensemble architectures to drastically lower variance and boost baseline model macro accuracy.
  - **Regularization Engines:** Embedded Ridge ($L_2$) and Lasso ($L_1$) mathematical penalties to mitigate parameter over-indexing and eradicate overfitting trends.
- **Data Architecture:** Designed a dedicated ERD schema mapping out relationships between individual athlete statistics, structural clubs, leagues, and calculated valuations.

## Tech Stack & Methods
- **Languages & Frameworks:** Python, Scikit-Learn, Pandas, NumPy
- **Visualizations:** Seaborn, Matplotlib, Relational ERD Diagrams
- **Core Methods:** Linear/Logistic Regression, Classification Trees, Regularization ($L_1/L_2$), Stacking/Voting Ensemble Methods.
-
