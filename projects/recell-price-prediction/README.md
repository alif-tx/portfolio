# ReCell: Pricing the Second Life of Devices

> 📓 **Active build. The full notebook drops here when it's ready.**

The refurbished device market does not reward guesswork. It rewards whoever prices inventory with mathematical precision before the competition finishes eyeballing spreadsheets. This repository houses a supervised machine learning pipeline built for ReCell, a startup staking its position in the used phone and tablet market. Pricing used hardware on intuition leaves margin on the table at scale. This project engineers a linear regression model that isolates exactly which device attributes drive resale value, turning a chaotic secondary market into a defensible pricing strategy.

### The Methodology & Unique Perspective
A pricing model is only as trustworthy as the assumptions it survives. This pipeline was built to earn that trust before a single prediction ships.

*   **Interrogating the Inputs:** Every feature, from camera specs and RAM to release year and days in service, gets profiled and validated before modeling. Missing values are handled deliberately, never dropped on reflex, preserving the full behavioral picture of the device market.
*   **Assumption Testing as a Discipline:** Linear regression makes promises it can only keep under specific conditions. Multicollinearity gets hunted down with VIF, residuals face normality and homoscedasticity checks, and the model is rebuilt until the diagnostics hold.
*   **Engineered Visuals:** Boardroom decisions are not driven by default charts. Custom correlation heatmaps and distribution visuals translate the statistical machinery into a narrative any stakeholder can act on.

### The Impact & Insights
This section gets written by the model, not before it. Three deliverables are locked in and under active development:

*   **The Drivers:** A ranked, coefficient-backed answer to which device attributes actually move resale price.
*   **The Scorecard:** Honest model performance reported on held-out test data, not just the training set.
*   **The Strategy:** A pricing recommendation ReCell could act on, translated from coefficients into business language.

### The Status
This is a live build. The dataset is staged, the pipeline architecture is locked, and the model is in active development with assumption diagnostics being run and rerun until they hold. Findings publish here the moment they survive scrutiny. Watch this space.

### The Stack
**Languages:** Python  
**Libraries:** Pandas, NumPy, Statsmodels, Scikit-learn, Seaborn, Matplotlib  
**Core Competencies:** Linear Regression, OLS, Multicollinearity Diagnostics (VIF), Residual Analysis, Feature Engineering, Predictive Modeling
