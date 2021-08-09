# Intro to Machine Learning with TensorFlow Nanodegree
# Unsupervised Learning
## Project: Identify Customer Segments

### Motivation
Applying unsupervised learning techniques to organize the general population into clusters, then use those clusters to see which of them comprise the main user base for the company. 
These clusters can then be used to direct marketing campaigns towards likely consumers for the mail-order sales company.


### Requirements
- Python
- NumPy
- pandas
- scikit-learn (v0.16)
- Matplotlib
- seaborn
- You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)
- [Anaconda](https://www.continuum.io/downloads) has these packages pre-installed.



### Data
Bertelsmann partners AZ Direct and Arvato Financial Solutions have provided two datasets one with demographic information about the people of Germany, and one with that same information for customers of a mail-order sales company.



### Results
1. Characteristic of people that overrepresented in the customer data compared to the general population (centroid_13):
	- 46 - 60 years old [ALTERSKATEGORIE_GROB=3.294843].
	- 30 - 40 km to nearest urban center [BALLRAUM=4.044076].
	- close to Older Families & Mature Couples [LIFE_STAGE=2.611905].
2. Characteristic of people that underrepresented in the customer data compared to the general population (centroid_7):
	- < 30 years old [ALTERSKATEGORIE_GROB=1.505096].
	- 20 - 30 km and less to nearest urban center [BALLRAUM=3.196383].
	- Young Couples With Children [LIFE_STAGE=1.025020].

