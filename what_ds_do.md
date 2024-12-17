# What data scientists really do and why we should stop focusing on modeling

*Understanding the Real Role of Data Scientists*

**TLDR;**

1) Models for analytics/business understanding 

2) Models for driving business success 

3) Metrics for AB testing 

4) many more feature engineering steps/evaluation steps 

— Advice: Build simple baselines and measure outcomes before jumping to an ML solution 

## 1. Models for Analytics and Business Understanding

Data scientists spend significant time creating models that help businesses understand their data and make informed decisions. This often involves:

- Exploratory data analysis to uncover patterns and insights
- Creating descriptive statistics and visualizations
- Building interpretable models to explain business phenomena — mostly rule-based
- Communicating findings to stakeholders

Real-life example:

> A retail company wanted to understand their customer base better. Instead of jumping into complex clustering algorithms, the data science team first created simple RFM (Recency, Frequency, Monetary) segments using basic rules. This helped identify key customer groups and informed marketing strategies. 

Guess what, stakeholders found it easier to comprehend than the previous embeddings-based solution.
> 

## 2. Models for Driving Business Success

Beyond understanding, models need to create tangible business value:

- Developing predictive models that solve specific business problems
- Implementing automated decision systems
- Optimizing existing business processes
- Creating data products that generate revenue

Real-life example:

> A warehouse implemented a basic time-series forecasting model to predict product demand. This simple model reduced overstock by 15% and stockouts by 20%, demonstrating that even straightforward predictive models can significantly impact business outcomes.

By choosing the business metrics: overstock and stockouts reduction, the model objective was clear for all team members and business stakeholders, reducing confusion and shortening timelines.
> 

## 3. AB Testing and Metrics

Rigorous testing is crucial for validating solutions:

- Designing robust experimental frameworks
- Selecting appropriate success metrics
- Conducting statistical analysis of results
- Making data-driven recommendations

Real-life example:

> An e-commerce company tested two versions of their checkout page. Using conversion rate as the primary metric and implementing a simple t-test, they found that the new design increased conversions by 8%. The clear experimental design made it easy to make a confident decision. 

You often hear brilliant ideas from the business stakeholders that not end up working as expected, as well as stupid solutions that for some reason make sense to the users. Experiment-driven decision making lets the users - and not your bosses - have the final say.
> 

## 4. The Reality of Feature Engineering

Most time is spent on data preparation rather than modeling:

- Data cleaning and validation
- Feature selection and creation
- Domain-specific transformations
- Feature validation and testing

Real-life example:

> A common situation in day-to-day data science:
> 
> - Original model had 500+ raw features and complex architecture but only achieved 72% accuracy
> - After domain expert consultation, engineered 50 meaningful features (like payment ratios, trend indicators, and behavioral metrics)
> - Simple logistic regression with these engineered features achieved 85% accuracy
> - Further feature selection identified 20 most important features, maintaining 83% accuracy while improving model interpretability
> 
> This showcases how thoughtful feature engineering using domain expertise and feature reduction can outperform extensive hyperparameter tuning of complex models. The simpler model was also faster to train, easier to maintain, and more interpretable for stakeholders.
> 

## Best Practices and Strategy

Key recommendations for effective data science:

- Start with simple baseline models to establish benchmarks
- Focus on measuring business outcomes rather than model metrics
- Only implement ML solutions when simpler approaches prove insufficient
- Maintain clear documentation and reproducible workflows

Remember: The goal isn't to build the most sophisticated model, but to solve business problems effectively. Sometimes a simple solution is the best solution.
