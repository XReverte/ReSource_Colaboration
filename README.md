# ReSource_Colaboration

## Table of contents
- README.md --> Project motivation | Goals | Methodology | Results | Conclussions | Limitations | Future Work | Contributions | Tools
- ReSource_Survey.ipynb --> Sample code used for the study
- ReSource_Labeler.ipynb --> Sample code used for labeling participants

![_e6aee582-4ef0-4fbd-893b-c5d9b250a457](https://github.com/XReverte/ReSource_Colaboration/assets/100844285/cbd9c83c-503f-410b-8df4-b61546726ac7)
*Image generated by Microsoft Bing (2023). graphic_art [1.0]*

## Motivation
The project arises from a **deep concern about the phenomenon of rural depopulation** affecting numerous communities worldwide. We observe with unease how these areas, which were once prosperous and vibrant, are experiencing a massive exodus of population, leaving behind a socio-economic and cultural void that threatens their survival.

This concern not only lies in the immediate impact on the quality of life of rural inhabitants but also in the loss of human resources, deeply rooted traditions, and the decline of cultural diversity, facing us with the possibility of **losing an invaluable heritage**, shaped over generations.

Motivated by the desire to address this challenge, I decided to join the Re-Source project, a **multidisciplinary team committed to confronting this circumstance from various perspectives**, aiming to raise awareness about the issue, fostering critical thinking to devise sustainable and effective solutions. I invite you to take a look at the project through:

Instagram: https://www.instagram.com/_re.source/

Youtube: https://www.youtube.com/@resource.community

![resource](https://github.com/XReverte/ReSource_Colaboration/assets/100844285/3f1a7f55-86db-4a0e-80b1-f9a733dc3a9c)

## Goals
The Re-Source project aims to create a **space for meeting and exchange** for all those interested in addressing the phenomenon of rural depopulation. Through a series of conferences led by experts from different fields, the project seeks to provide a comprehensive understanding of the issue, fostering debate and active participation among attendees.

Furthermore, after identifying and understanding the complex dynamics behind this phenomenon, the project aims to drive the creation of inclusive and sustainable strategies to promote the economic, social, and cultural development of rural communities at risk of depopulation. To achieve this, practical sessions are conducted where participants work in groups to **identify and design solutions tailored to the specific needs of each village**.

As part of this process, my personal objective is to **develop an effective methodology for segmenting participants** into working groups and assigning villages according to their preferences. This segmentation not only aims to facilitate optimal distribution based on group interests, promoting greater understanding among members, but also seeks intergroup diversity of perspectives, thus enriching the collaboration process and the quality of proposed solutions.

Furthermore, in my role as a happiness researcher, I contribute to the project by providing insights and reflections on **how to address rural depopulation from a perspective focused on the well-being** and quality of life of its inhabitants.

![resource_4](https://github.com/XReverte/ReSource_Colaboration/assets/100844285/8999a1ae-a1c9-4130-96f1-7fe6fdf3c2e7)

## Methodology
Our methodology begins with the **design of a carefully crafted survey** to capture respondents' preferences regarding the characteristics of the ideal village they would like to live in. These questions cover aspects such as climate, geography, population, and other relevant factors, as well as gathering information to create a personalized profile of each respondent.

The survey was distributed and **completed by approximately 100 external participants**, providing a representative and diverse sample of opinions.

Once the dataset was collected and prepared, we proceeded to cluster it using **k-means**. We identified the optimal number of clusters using methods such as Elbow and Silhouette, and fine-tuned the model's hyperparameters using techniques such as grid search to optimize its performance.

Subsequently, we employed a **Gradient Boosting model to determine the importance of features in predicting the group** to which each respondent belongs. This process was conducted iteratively, continuously refining the model through feature selection and engineering techniques to enhance its predictive capability.

Once the clustering architecture was established, we conducted **statistical analysis to identify significant differences between groups**, allowing us to characterize them and facilitate the optimal assignment of villages to each group.

Finally, project participants were invited to complete the same survey, enabling us to **predict their group membership** based on distances to centroids and assign them to the corresponding groups accurately and precisely.

![pipeline3](https://github.com/XReverte/ReSource_Colaboration/assets/100844285/c422e484-f1e7-4e24-b6f5-6d783b1bdeeb)

## Results and conclusions
Based on the project's work dynamics and considering that the appropriate number of groups should fall between 3 and 5, we decided to **set k=4 as the number of groups**, although this choice was not the most optimal.

It is important to highlight that, according to the analysis conducted using Gradient Boosting, the variables that demonstrated the greatest importance in predicting the groups were: **whether the village was coastal or not**, **preference for outdoor activities**, and a variable derived from feature engineering techniques that attempted to determine the preferred **demographic volume** based on various factors.

![importance](https://github.com/XReverte/ReSource_Colaboration/assets/100844285/e301e1f9-946d-4bae-ad1e-9839f62e3b27)

Upon performing an analysis of significant differences between the groups, each group was characterized as follows:
- Group 1: Low population, located in mountainous areas, with adventure activities.
- Group 2: Large population, situated in forested areas.
- Group 3: Low population, located in rural areas, with spiritual activities.
- Group 4: Large population, located in coastal areas, with beach-related activities.

These results provide a detailed understanding of group preferences, allowing for an **informed allocation of villages** tailored to the specific needs of each group.

![Población](https://github.com/XReverte/ReSource_Colaboration/assets/100844285/14b70673-276a-4feb-9b11-365f13f8c58c)

![Zona](https://github.com/XReverte/ReSource_Colaboration/assets/100844285/e9c414a7-d99f-4145-806d-1fc5574b695d)

![PerfilPersonal](https://github.com/XReverte/ReSource_Colaboration/assets/100844285/a45a385f-e56c-415d-8e1f-98912c77ca08)

## Limitations
The sample size of approximately 100 respondents could be considered **limited in representing the diversity** of preferences and characteristics of all rural communities affected by depopulation.

There is a possibility of bias in the results as the participants **may not be entirely representative** of the target population.

Although we aimed for a thorough analysis, the interpretation of the results may be subject to different interpretations and **may not fully capture the complexity and variability of preferences and characteristics of rural communities**.

## Contributions
The project contributed to **raising awareness** within the community about the issue of rural depopulation, fostering debate and reflection on possible solutions.

Through conferences and practical activities, critical thinking was promoted among participants, stimulating the generation of **innovative and sustainable ideas to address the issue**.

The project brought together professionals from different fields and disciplines, facilitating the **exchange of knowledge and perspectives** to address rural depopulation from diverse and complementary approaches.

## Tools
- Technologies: Python | Excel | Google Forms | Coogle
- Libraries: numpy | pandas | matplotlib | seaborn | graphviz | sklearn | scipy | statsmodels | skmultilearn | xgboost | prince | itertools
- Machine Learning Models: K-Means | Gradient Boosting 
