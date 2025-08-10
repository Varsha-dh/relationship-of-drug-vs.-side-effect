
Exploratory Data Analysis on Drugs, Side Effects, and Medical Conditions
Author: Varsha Dudhat


1. Objective
The aim of this project is to analyze the relationships between drugs, their side effects, and the medical conditions they treat. The study also explores the ratings and reviews associated with these drugs to gain insights into patient satisfaction and reported experiences.

2. Dataset Overview
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

3. Data Cleaning & Preprocessing
Filled categorical missing values with "unknown".

Filled numeric missing values with -1 for easier identification in analysis.

Performed text normalization and synonym handling for side_effects.

Removed invalid entries.

Prepared cleaned dataset for statistical and visual analysis.

4. Exploratory Data Analysis (EDA)
4.1 Top 10 Side Effects
Most common side effects include:

Swelling of the throat, lips, or tongue

Hives

Facial swelling

Nausea

Vomiting

Itching

Difficulty breathing

Dizziness

4.2 Distribution of Ratings
Ratings are positively skewed — most ratings fall between 6–10.

Low or zero ratings may indicate dissatisfaction or placeholder values from missing data handling.

4.3 Top 10 Drugs by Reviews
Highly reviewed drugs:

Phentermine

Bupropion

Contrave

Escitalopram

4.4 Top Drugs by Medical Condition
Drug Name	Medical Condition	Count
Acyclovir	Herpes	2
Fluocinolone	Eczema	2
Minocycline	Acne	2
Others	Single occurrences	1

Insight:
Acyclovir–Herpes, Fluocinolone–Eczema, and Minocycline–Acne are the most frequent drug–condition pairs. Others are niche or rarely used.

4.5 Drug Rating Analysis by Class
Median ratings for most drug classes: 6–8 (generally favorable).

High-performing classes: Interleukin inhibitors, antacids, some analgesics.

Lower median & higher variability: Urinary antispasmodics, laxatives, mineral supplements.

Outliers present in almost every class — indicating individual differences in drug response.

5. Statistical Analysis
Chi-Square Test:

No statistically significant relationship between drug and medical condition.

Extremely strong and statistically significant association between drug and reported side effects.

6. Key Findings
Drug Ratings: Majority of drugs receive high ratings, indicating general satisfaction.

Top Drugs for a Condition: Limited high-frequency drug–condition pairs.

Side Effects: Certain severe allergic reactions and gastrointestinal symptoms are common.

Class Variability: Drug classes differ significantly in both effectiveness and tolerance.

7. Limitations & Future Work
Data Limitation: Limited number of records per drug reduces statistical power and may hinder robust identification of drug–side effect–condition associations.

Future Work:

Expand dataset to include more reviews per drug.

Perform sentiment analysis on user reviews.

Explore temporal trends in drug ratings and side effects.
