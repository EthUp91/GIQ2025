__UK_Petitions.zip__

This file contains the petitions dataset s from the UK Parliament’s online petition system (https://petition.parliament.uk), consisting of 50,466 petitions, each labeled as either admitted or rejected, submitted between March 2020 and January 2024. For the experiments, 46,465 petitions were used after filtering out entries that were incomplete or lacked category labels.

__Taiwanese_Petitions.ipynb__

This notebook contains the code used to develop a multi-label classifier based on the Taiwanese petition dataset. The classifier is designed to predict one or more relevant categories for each petition using labeled data spanning from September 2015 to January 2024.

__Taiwanese_Petitions.csv__

This dataset consists of 658 petitions collected from Taiwan’s official government petition platform, Join (https://join.gov.tw). Each petition is assigned one or more of 12 predefined categories (e.g., transportation, environment). The petitions cover the period from September 2015 to the end of January 2024. Only petitions with clearly assigned categories on the platform were included in the dataset for the experiments.

__UK_Petitions.ipynb__

This notebook contains the code used to develop the user-side component of the system, which classifies petitions as potentially admitted or rejected. It also incorporates the SHAP values method to highlight specific words in each petition that may contribute to an increased probability of rejection.
