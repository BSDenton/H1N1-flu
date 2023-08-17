# H1N1-flu

This project was completed for an MSc module 'Data Science with Machine Learning'. The coursework specification asked that we design a research project involving the National 2009 H1N1 Flu Survey data. The only requirements were that we showed evidence of at least two approaches to data preprocessing, handling missing data, and modelling. The project received a grade of 80%.

Full report can be viewed: https://github.com/BSDenton/H1N1-flu/blob/main/H1N1FluSurvey-Report.pdf

Juptyer notebook can be viewed: https://github.com/BSDenton/H1N1-flu/blob/main/H1N1FluSurvey.ipynb

## Abstract
Vaccine hesitancy (a reluctance or refusal of vaccination despite the availability of vaccination services) has been a longstanding barrier that public health campaigns have struggled to overcome. Recent years have seen the re-emergence of viruses in countries where they were thought to have been eliminated, such as measles reappearing within the United Kingdom and USA. This, combined with the world-altering impact of the COVID-19 pandemic, has shown the consequence that decreased vaccine uptake can have upon public health at a national and global level. It has highlighted the need for accurate predictive models, which can be used to inform public health officials and allocate health care resources efficiently. 

Predictive models are most useful in a real-world application when they can provide accurate predictions based on data that are easy and reliable to collect. However, self-reported behavioral data are more likely to contain inaccurate values, as they require the participant to honestly assess their own behavioral patterns. This paper therefore aims to determine whether data from the National 2009 H1N1 Flu Survey can be used to train a model for predicting vaccine uptake, without the use of the behavioral features collected in the original survey. 

Multiple modelling approaches are compared; best results were seen using an ExtraTrees model, and with casewise deletion being used to deal with missing values. This model predicted whether participants had received either the H1N1 or seasonal flu vaccination with an AUC ROC score of 0.85, and an F1-score of 0.79. This paper shows that collecting self-reported behavioral data may not be necessary to create well-performing predictive models for vaccine uptake. This information can be used to better inform the design of future surveys investigating vaccination patterns. We also provide an adequate model for predicting H1N1 and seasonal flu vaccination uptake within a population.
