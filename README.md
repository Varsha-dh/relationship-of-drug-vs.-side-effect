
**Drug Relationship Analysis Project**

**📌** **Overview**

This project aims to analyze the relationships between drugs, side effects, and medical conditions to uncover significant patterns. Using statistical analysis and data visualization, the goal is to identify which drugs are most associated with specific side effects under certain medical conditions.


🎯 **Objective**

The aim of this project is to analyze the relationships between drugs, their side effects, and the medical conditions they treat. The study also explores the ratings and reviews associated with these drugs to gain insights into patient satisfaction and reported experiences.

📂. **Dataset Overview**

The dataset contains 2931 rows and 17 columns, including key variables such as:

drug_name – Name of the drug

medical_condition – Condition the drug treats

side_effects – Commonly reported side effects

generic_name – Generic version of the drug

drug_classes – Classification (e.g., antibiotic, antihistamine)

brand_names – Commercial names of the drug

activity – Status (active/inactive)

rx_otc – Prescription (Rx) or over-the-counter (OTC)

pregnancy_category – Risk category during pregnancy

csa – Controlled Substances Act schedule (if applicable)

alcohol – Alcohol interaction warnings

related_drugs – Similar or related drugs

medical_condition_description – Condition description

rating – Average user rating

no_of_reviews – Number of user reviews

drug_link – Reference link for the drug

medical_condition_url – Reference link for the condition

Missing Data: ~14% missing values, mainly in rating, no_of_reviews, alcohol, and related_drugs.

🛠️. Methodology

**1.Data Cleaning**

Removed duplicates and irrelevant text.

Standardized side effect names.

Filtered unwanted terms (e.g., "call your doctor at once if you have").

**2.Exploratory Data Analysis (EDA)**

Top 10 drugs by reviews.

Most frequent side effects.

Side effects per medical condition.

**3.Statistical Analysis**

Chi-square test to find significant drug–side effect relationships.

**4.Visualization**

Bar plots for top drugs and side effects.

Heatmaps for drug–side effect associations.

📊 **Key Findings**

Drug Ratings: Majority of drugs receive high ratings, indicating general satisfaction.

Top Drugs for a Condition: Limited high-frequency drug–condition pairs.

Side Effects: Certain severe allergic reactions and gastrointestinal symptoms are common.

Class Variability: Drug classes differ significantly in both effectiveness and tolerance.

📌 **Limitations & Future Work**

Data Limitation: Limited number of records per drug reduces statistical power and may hinder robust identification of drug–side effect–condition associations.

Future Work:

Expand dataset to include more reviews per drug.

Perform sentiment analysis on user reviews.

Explore temporal trends in drug ratings and side effects.
 
 **Author
 Varsha Dudhat**
