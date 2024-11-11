# Multilabel-Multiclass-Sentiment-and-Emotion-Dataset-from-Indonesian-Mobile-Application-Review
**Authors**: Riccosan* & Karen E. S.

## Abstract
Reviews are a person's way of expressing feedback on something in the form of criticism and ideas. Reviews of mobile apps are a type of user feedback that focuses on the performance and look of a mobile application and is typically featured on the download page of a mobile application, such as in the Apps Store. Because it comprises a person's feelings and emotions, whether they are joyful, sad, hostile, or indifferent toward a mobile application, the review data is textual and may be gathered and utilized as material for creating a textual dataset. This work creates a multi-label multi-class Indonesian-language dataset based on public reviews of mobile applications with sentiment and emotional values. Another factor supporting the creation of this dataset is the fact that there are still a limited number of textual datasets based on the Indonesian language that is multi-label multiclass for performing sentiment analysis tasks, particularly those linked to text classification tasks. The data generated by this research was cleaned and handled during the pre-processing step and was annotated with 3 sentiments, namely positive, negative, and neutral, as well as 6 emotions, namely anger, fear, sad, happy, love, and neutral which make this dataset multiclass. This dataset created is multi-label since each sentence in it has two labels.

**Key Words:** Sentiment, Emotion, Text Classification, Dataset, Multilabel, Multiclass, Mobile Application Review, Indonesia

## Data Format
Raw, Filtered, Annotated

## About The Data
This dataset was created to carry out text classification tasks in Indonesian as part of Natural Language Processing utilizing multiclass multilabel data for sentiment analysis. This dataset is multiclass because it is annotated with 3 sentiment labels (positive, negative, and neutral) and 6 emotion labels (sad, fear, anger, happy, love, and neutral), and multilabel because each sentence containing both labels, a sentiment and an emotion label.

Data distribution based on SENTIMENT CLASS:
| **Sentiment_Class** |     Negative    |     Positive    |     Neutral    |
|---------------------|-----------------|-----------------|----------------|
| **Total_Data**      | 7,721           | 6,523           | 7,453          |

Data distribution based on EMOTION CLASS:
| **Emotion_Class** |     Sad      |     Anger    |     Fear     |     Happy    |     Love    |     Neutral    |
|-------------------|--------------|--------------|--------------|--------------|-------------|----------------|
| **Total_Data**    |     3,753    |     2,697    |     1,271    |     6,330    |     193     |     7,453      |

## Pre-processing Stage
The Data Pre-processing flow is made up of 9 sub-processes. The basic data pre-processing procedure is employed at this step to remove unnecessary data [1], in the form of:
1. Remove basic duplicates,
2. Remove URLs,
3. Remove mention/hashtag/special character,
4. Remove emoji,
5. 5emoves dupes,
6. Remove enter/new line format.

After the data has been cleansed, Split Data (sub-process 7) is applied based on the mobile app rating level that divides data into 5 dataframes. The column carrying Mobile Apps rating level was removed (sub-process 8) after the data was separated since the data created via this research only intended to take pure textual data. The final step (sub-process 9) in Data-Preprocessing is to save every dataframes in ".CSV File" format.

## Additional Information
To access this dataset research paper in order to get a more elaborate understanding, please access the DOI:
**(https://doi.org/10.1016/j.dib.2023.109576)**

## Paper References
1. E. Nugraheni, Indonesian Twitter Data Pre-processing for the Emotion Recognition, 2019 International Seminar on Research of Info. Tech. & Intelligent Systems (ISRITI). (2019) 58-63. Yogyakarta, Indonesia: IEEE. https://doi.org/10.1109/ISRITI48646.2019.9034653.
2. R. A. Hasan, T. Sutikno and M. A. Ismail, A Review on Big Data Sentiment Analysis Techniques, Mesopotamian Journal of Big Data. 2021 (2021) 6-13. https://doi.org/10.58496/MJBD/2021/002.
3. Riccosan and K. E. Saputra, Multilabel Multiclass Sentiment and Emotion Dataset from Indonesian Mobile Application Review, GitHub, 2023. https://zenodo.org/badge/latestdoi/670026526.
4. A. H. Ali, H. Kumar and P. J. Soh, Big Data Sentiment Analysis of Twitter Data, Mesopotamian Journal of Big Data, 2021 (2021) 1-5. https://doi.org/10.58496/MJBD/2021/001.
5. N. D. Zaki, N. Y. Hashim, Y. M. Mohialden, M. A. Mohammed, T. Sutikno and A. H. Ali, A real-time big data sentiment analysis for iraqi tweets using spark streaming, Bulletin of Electrical Engineering and Informatics. 9,  4 (2020) 1411-1419. https://doi.org/10.11591/eei.v9i4.1897.
6. P. R. Shaver, U. Murdaya, & R. Chris Fraley, Structure of the Indonesian Emotion Lexicon, Asian J. of Soc. Psyc. 4 (2001) 201-224. https://doi.org/10.1111/1467-839X.00086.
7. P. Shaver, J. Schwartz, D. Kirson, & C. O'Connor, 1987. Emotion Knowledge: Further Exploration of a Prototype Approach. Journal of Personality Aid Social Psychology. 52, 6. 1061-1086. https://doi.org/10.1037//0022-3514.52.6.1061.
8. W. G. Parrott, Emotions in social psychology: Essential readings (Eds.), Psychology Press, New York, USA, 2001.
9. A. J. Viera & J. M. Garrett, 2005. Understanding Interobserver Agreement: The Kappa Statistic. Family Medicine. 37, 5. 360-363. PMID: 15883903.

### Dataset DOI (Digital Object Identifier) Number by Zenodo
[![DOI](https://zenodo.org/badge/670026526.svg)](https://zenodo.org/badge/latestdoi/670026526) <br>
Zenodo provided the dataset DOI for this research, which can be found at the following link: <br>
https://zenodo.org/badge/latestdoi/670026526

### Licensed
Shield: [![CC BY-NC-ND 4.0][cc-by-nc-nd-shield]][cc-by-nc-nd]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-NoDerivs 4.0 International License][cc-by-nc-nd].

[![CC BY-NC-ND 4.0][cc-by-nc-nd-image]][cc-by-nc-nd]

[cc-by-nc-nd]: http://creativecommons.org/licenses/by-nc-nd/4.0/
[cc-by-nc-nd-image]: https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png
[cc-by-nc-nd-shield]: https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg
