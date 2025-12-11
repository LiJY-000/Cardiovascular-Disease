# Cardiovascular-Disease

This report summarizes the major findings presented in the visual analysis of heart disease risk factors，highlight which clinical features strongly differentiate individuals with and without cardiovascular disease (CVD).

1. Most Important Predictors of Heart Disease
A feature-importance analysis identifies ST_Slope, Exercise-Induced Angina, Sex, Oldpeak, and Cholesterol as the strongest predictors of cardiovascular disease. These variables show the clearest separation between high-risk and low-risk individuals and therefore carry the greatest weight in predictive modeling.

2. ST Segment Slope (ST_Slope)
The ST segment slope during peak exercise is a clinically significant indicator of heart strain.
* Up-sloping and flat slopes are associated with a much higher probability of heart disease.
* Down-sloping ST segments, conversely, appear less frequently in heart disease cases.
This reflects changes in myocardial oxygen supply during exercise, making ST_Slope one of the strongest diagnostic signals.

3. Exercise-Induced Angina (ExerciseAngina)
Exercise-induced chest pain is one of the most direct symptoms of compromised coronary blood flow.
* Individuals reporting angina during exercise show markedly higher rates of heart disease.
* Nearly 89% of those with angina fall in the heart-disease group, compared with only 36% among those without.
This indicator aligns with clinical understanding that exertional chest discomfort is a major early symptom of coronary artery disease.

4. Cholesterol Levels
Cholesterol distribution reveals several important patterns:
* Most heart-disease patients cluster between 0–250 mg/dL, with extremely high density at very low values, especially near 0.
* A cholesterol value of 0 highly correlates with heart disease in this dataset (likely a coding or data-entry artifact but still impactful).
* Around 200–250 mg/dL, differences between healthy and diseased individuals narrow, making classifications less clear.
Despite known biological complexities, cholesterol remains a moderately strong risk predictor.

5. Gender Differences
Gender-based comparison shows a clear disparity:
* 63% of males in the dataset have heart disease.
* Only 26% of females fall into the same category.
This reflects the well-established epidemiological pattern that men experience cardiovascular disease earlier and more frequently than women.

6. Oldpeak (ST Depression)
Oldpeak measures ST-segment depression relative to rest, representing impaired myocardial perfusion during physical stress.
* Values near zero indicate lower risk.
* As Oldpeak increases — particularly from 1.25 to 2.0 — the likelihood of heart disease rises substantially.
This variable provides quantifiable evidence of ischemia and is one of the more interpretable features in the dataset.

Conclusion
Across multiple visual analyses, the strongest contributors to cardiovascular disease risk include exercise-related ECG changes (ST_Slope and Oldpeak), symptoms such as ExerciseAngina, biological sex, and lipid-related measures such as Cholesterol.
These findings align with clinical knowledge and demonstrate how physiological stress responses — recorded through ECG signals and exercise symptoms — can offer powerful early warnings for heart disease.



