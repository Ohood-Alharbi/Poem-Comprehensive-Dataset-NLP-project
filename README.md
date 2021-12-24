# Project proposal
# Poem-Comprehensive-Dataset-NLP-project
![GitHub Logo](https://i.pinimg.com/originals/a1/9d/6d/a19d6d60c15c08a0369d971867aa2329.jpg)
# Description:
Arabic poetry is the earliest form of Arabic literature. Present knowledge of poetry in Arabic dates from the 6th century, but oral poetry is believed to predate that .This project about Arabic PCD (APCD) dataset to do EDA and using NPL algorithms.The Arabic dataset is scraped mainly from الموسوعة الشعرية and الديوان. After merging both, the total number of verses is 1,831,770 poetic verses.

# Problem state:
The aims of this project is to apply the most important natural language processing techniques and starting with implementing all text preprocessing in "Arabic"  then using clssification model to classify each Poet_name and his poetries and we will using topic modeling to cluster each peorties depend on poetry types or poetry rhymes.

# Data Description:
This dataset contains 1,831,770  observations and 8 columns. it provided by this URL :   
https://hci-lab.github.io/ArabicPoetry-1-Private/ 
## Features
| Feature name          | Data_type                       | Description                                         |       
|-----------------------|---------------------------------|-----------------------------------------------------|
| Generation            | Object                          |The time period in which the poet lived
| Poet_name             | Object                          |Poet's name
| Divan                 | Object                          |It is a book that contains poems by one poet
| Ryhme                 | Object                          |The concept of rhyme refers to the last word in a poetic line.
| Poem_type             | Object                          |the weights of the poem 
| Left_side             | Object                          |Left side of verse
| Right_side            | Object                          |Right side of verse.
| Verse                 | Object                          |Verse of poem 

# Tools:
 * Technologies: Python, Jupyter notebook.

* Libraries: NumPy, Pandas, Sklearn, Matplotlib, Seaborn, Tableau, nltk , pyarabic 

# Models:
*	K-mean ++

*	NMF

*	LDA

## Developers:
* [Ohood Alharbi](https://github.com/Ohood-Alharbi)
* [Ajwad Saleh](https://github.com/Ajwadsm)
