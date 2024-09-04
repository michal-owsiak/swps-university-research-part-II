<div align="center">
    <img src="public/swps_logo.png" width="1800" alt="SWPS University logotype">
</div>

## **A study of Poles' psychedelic and non-psychedelic mystical experiences: Lingustic analysis**

This repository contains a [Jupyter Notebook](https://github.com/michal-owsiak/swps-university-research-part-II/blob/main/linguistic_analysis.ipynb) that focuses on lingustic analysis of the descriptions of psychedelic and non-psychedelic mystical experiences.

## **Data collection**

The analyzed descriptions were collected through an online survey distributed from February 17, 2023, to March 29, 2023. 

## **Tools used**

**Languages, frameworks and environments:**
```
> Jupyter Notebook
> Python
> IPython
> Markdown
```
**Libraries and packages:**
```
> pandas
> NumPy
> SciPy
> scikit-learn
> NLTK
> transformers
> statsmodels
> wordcloud
> PIL
> Matplotlib
```
**APIs and pre-trained models:**
```
> DeepL REST API
> EmoRoBERTa
```



## **Data analysis and visualization**

### **Data wrangling and cleaning**

Using plain `Python` along with `pandas` and `NumPy` predefined functions, the following steps were performed:

- Merging duplicated variables into consistent dataset
- Recoding questionnaires' scorings
- Calculating summed results
- Cleaning and preparing data for analysis

### **Data analysis**

- Calculating word frequency distribution using `NLTK` for tokenization and `wordcloud` for stopwords.
- Conducting series of correlation analysis using `CountVectorizer` from `scikit-learn` and `pearsonr` function from `SciPy`.
- Performing emotional sentiment NLP analysis using `EmoRoBERTa` pre-trained model from `transformers` library.

### **Data visualization**

The results of the study were visualized as bar plots employing `Matplotlib` library and as word clouds using `wordcloud` library. 

## **Results and conclusions**

The analysis revealed that descriptions of complete mystical experiences often emphasize positive emotions and existential themes, such as love and cosmic concepts, while negative emotions and factual terms are more associated with less intense experiences. Significant differences were noted in the frequency of specific emotions like admiration and fear between the two groups, with complete experiences showing more positivity and less negativity. Overall, the findings highlight how language reflects the intensity and nature of mystical experiences, with positive emotional and existential themes prevalent in more profound experiences.


## **Authorship**

The original research was performed and presented repository was created by Michał Owsiak. The author declares no potential conflicts of interest with respect to the research, authorship, and/or publication of this repository.
