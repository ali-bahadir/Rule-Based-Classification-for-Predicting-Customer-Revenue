# Rule-Based-Classification-for-Predicting-Customer-Revenue
Rule-Based Classification project for segmenting customers and predicting potential revenue based on demographic data. Implements Python, Pandas, and data preprocessing techniques to create level-based personas and customer segments.

## Business Problem
The goal of the project is to create level-based customer personas using demographic features, segment customers, and predict the average revenue that new customers might bring to the company. For instance, we aim to determine how much a 25-year-old male iOS user from Turkey would contribute on average.

---

## Dataset Information
The dataset, `persona.csv`, contains demographic information and spending habits of customers. Key features include:

- **PRICE**: Amount spent by the customer
- **SOURCE**: Device type used (Android/iOS)
- **SEX**: Gender of the customer
- **COUNTRY**: Customer's country
- **AGE**: Customer's age

## Project Tasks
1. Load the dataset and explore general information.
2. Analyze unique values and their frequencies (e.g., devices, prices).
3. Calculate aggregated metrics such as revenue by country and device type.
4. Create level-based personas by combining demographic features.
5. Categorize the `AGE` variable into meaningful age ranges.
6. Segment the personas based on average revenue.
7. Predict the revenue potential for new customers based on their profiles.
