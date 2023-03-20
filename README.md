# Selection_of_patients_for_Diabetes_drug_testing

## Diabetes Drug Testing

As a data scientist in a dynamic healthcare startup, you have been tasked with designing a predictive model to identify suitable candidates for Phase III clinical trial testing of a groundbreaking diabetes drug. The drug in question is a highly unique and sensitive treatment, necessitating meticulous administration, screening, and monitoring over a minimum period of 5-7 days in a hospital setting. With access to a patient dataset provided by a client partner, your goal is to build a regression model to predict estimated hospitalization time and subsequently filter the most appropriate patients for this study. The focus shall be on identifying individuals with a high likelihood of hospitalization for the requisite duration while minimizing additional expenses incurred during drug administration and monitoring.

To achieve this objective, you shall develop a comprehensive regression model utilizing a synthetic dataset built off the UCI Diabetes readmission dataset, which has been denormalized for line-level augmentation. The model shall provide expected days of hospitalization time, which can be utilized to make binary predictions on whether to include or exclude a patient from the clinical trial.

This project shall serve to highlight the critical significance of constructing an accurate and appropriate data representation at the encounter level, with the utmost care given to filtering and preprocessing/feature engineering of key medical code sets. Furthermore, as a part of this project, you shall analyze and interpret the model for any inherent biases across critical demographic groups.

Please note that, due to healthcare PHI regulations such as HIPAA and HITECH, access to publicly available datasets is restricted, and some datasets require training and approval. As such, we shall utilize a dataset modified for this course from UC Irvine, which, though limited in its representation of some key features such as diagnosis codes, shall suffice for the purposes of this exercise.





Regenerate
[
](https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008)
In this repository, I've created a regression model that can forecast a patient's hospital stay and provide a range of uncertainty estimates so that you can rank the predictions depending on the uncertainty range.

This Project is licensed under MIT License - see the LICENSE.md
