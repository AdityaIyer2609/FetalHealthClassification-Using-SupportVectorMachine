# FetalHealthClassification-Using-SupportVectorMachine
Reduction of child mortality is reflected in several of the United Nations' Sustainable Development Goals and is a key indicator of human progress. The UN expects that by 2030, countries end preventable deaths of newborns and children under 5 years of age, with all countries aiming to reduce under‑5 mortality to at least as low as 25 per 1,000 live births.  Parallel to notion of child mortality is of course maternal mortality, which accounts for 295 000 deaths during and following pregnancy and childbirth (as of 2017). The vast majority of these deaths (94%) occurred in low-resource settings, and most could have been prevented.  In light of what was mentioned above, Cardiotocograms (CTGs) are a simple and cost accessible option to assess fetal health, allowing healthcare professionals to take action in order to prevent child and maternal mortality. The equipment itself works by sending ultrasound pulses and reading its response, thus shedding light on fetal heart rate (FHR), fetal movements, uterine contractions and more.

The features in the dataset are,
baseline value — Baseline Fetal Heart Rate (FHR)
accelerations — Number of accelerations per second
fetal_movement — Number of fetal movements per second
uterine_con — Number of uterine contractions per second
light_decelerations — Number of LDs per second
severe_decel — Number of SDs per second
prolongued_decel — Number of PDs per second
abnormal_short — Percentage of time with abnormal short term variability
mean_value_of_sh — Mean value of short term variability
percentage_of_ti — Percentage of time with abnormal long term variability


In this work, I developed a prediction system by implementing three different types of Support Vector Machine Classifier which both the pregnant women and practitioners can make use of.  This model is trained with the clinical dataset of 96 pregnant women and used to process data to predict fetal anomaly status based on the maternal and clinical data.
