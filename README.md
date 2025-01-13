<h1> Optimizing Hotel Revenue: A Machine Learning Approach to Cancellation Prediction </h1>

## 1. Project Overview
This project analyzes business data to extract insights, improve decision-making, and identify key trends in the hospitality industry, specifically regarding hotel booking cancellations. The primary focus is to reduce cancellations, which impact both revenue and operational efficiency. By predicting cancellations, the hotel can implement strategies like overbooking, last-minute discounts, and resource optimization. Key goals include increasing revenue, enhancing operational efficiency, and improving customer experience by identifying high-risk segments and minimizing uncertainty. The project uses a classification model with a focus on the ROC-AUC metric to balance false positives and negatives, ultimately improving profitability and operational planning.

Key Objectives:
- Objective 1: Increase Revenue -> Reduce financial losses from cancellations by maximizing room occupancy through strategies like overbooking and last-minute discounts.
- Objective 2: Operational Efficiency -> Minimize uncertainty in resource planning by optimizing staff allocation, room inventory management, and service scheduling based on cancellation predictions.
- Objective 3: Enhance Customer Experience -> Improve customer loyalty and satisfaction by identifying high-risk cancellation segments and offering flexible policies tailored to those customers.

## 2. Data Sources
- [[Dataset 1](https://drive.google.com/file/d/1WzkqwptNsC285arNV7X4x7E5QcA7UX3W/view?usp=sharing)] - Hotel Booking Demand Data

## 3. Technologies Used
- Programming Language: Python (Pandas, NumPy, Scikit-learn)
- Visualization: Matplotlib, Seaborn
- Machine Learning: Scikit-learn (Logistic Regression, Decision Trees, etc.)
- Version Control: Git
- Development Environment: Jupyter Notebook

## 4. Project Structure

```
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks.
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
└── src                <- Source code for use in this project.

```

## 5. Summary of Finding
### 5.1 Business Insight

- **Improved Revenue Recovery:** The model has successfully increased the Revenue Recovery Rate (RRR) to 12.24%, exceeding the initial 10% target, demonstrating its effectiveness in recovering lost revenue from cancellations.

- **Cost Savings from Reduced Losses:** By decreasing losses from False Negatives (undetected cancellations) from IDR 205,500,000 to IDR 60,150,000, the model has saved the business IDR 145,350,000, directly boosting profitability.

- **Effective Balance Between Overbooking and Cancellations:** The model has successfully balanced the risks of False Positives (overbooking) with the revenue recovered from cancellations, showing its ability to optimize operational planning and minimize unnecessary overbooking.

### 5.2 Actionable Recommendation

- **Refine Overbooking Strategy:** To further enhance revenue recovery, the hotel should incorporate additional risk factors such as seasonal trends, local events, and booking patterns into the overbooking strategy. This will help in better predicting high-risk cancellations and improving booking management.

- **Introduce Flexible Cancellation Policies for High-Risk Customers:** The hotel could consider offering flexible cancellation policies or incentives for customers identified as high-risk, thereby encouraging them to retain their bookings and reducing overall cancellations.

- **Leverage Last-Minute Promotions:** Using the model's predictions, the hotel can introduce targeted last-minute deals or special promotions to quickly fill canceled rooms, benefiting both the customers and the business by optimizing revenue recovery and enhancing customer loyalty.

## 6. Contact
- Name : Melin Ayu Safitri
- Email : melinayusafitri@gmail.com
- Linkedin: linkedin.com/in/melinayusafitri
