✅ 📊 Key Insights from the Insurance Cost Prediction Project
1. Smokers Pay Significantly Higher Medical Charges

The analysis shows that smoking is the strongest predictor of medical insurance charges.

Average charges for smokers were 3–4 times higher than non-smokers.

Scatterplots and correlation heatmaps highlight smoking as a major cost-driving risk factor.

2. BMI Has a Positive Relationship With Charges

Individuals with a higher Body Mass Index (BMI) tend to incur higher charges.

The trend becomes more prominent for BMI > 30 (obesity range).

Feature engineering (BMI categories) confirmed that obesity drives costs upward.

3. Age Strongly Impacts Medical Expenses

Medical charges increase almost linearly with age.

Older individuals (>50 years) show significantly higher predicted costs.

Age is one of the highest contributors in feature importance plots.

4. Region Has Minimal Influence

The dataset contains people from 4 regions: northeast, northwest, southeast, southwest.

Charges do not vary drastically between regions.

Chi-square tests also show region and charges have weak association.

5. Gender Has Little to No Effect

Male vs female comparison shows no significant difference in charges.

No major correlation visible in heatmaps.

6. Families With More Children Tend to Have Higher Charges

The number of children shows a mild positive correlation with charges.

This effect is small but noticeable.

7. Logistic Transformations & One-Hot Encoding Improved Model Performance

Converting categorical columns (sex, smoker, region) into dummy variables helped the model learn better.

Label encoding was useful for initial preprocessing.

8. Important Features (from Feature Importance Plot)

Top contributors to medical cost prediction were:

Smoker

Age

BMI

Number of children

Less important features:

Region

Gender
