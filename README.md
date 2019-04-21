# data-science-program-design
A repository for the final project for the course MIE1624 -- Introduction to Data Science and Analytics. 

The final product of this project is the design of 4 components:

* a graduate university course introducing Data Science

* a technical Master of Data Science and Analytics (MSDA) degree program

* a managerial degree program related to Data Science and Analytics

* an EdTech startup effort assisting Data Science education

---

## The results can be found in the following notebooks and folders:

### Data and plots

folder **data** contains full HTMLs of job postings scraped from Indeed.ca and .csv's with skills and data parsed from these postings.

folder **final plots** contains the **frequency barcharts and hierarchical clustering dendrograms of skills**

* two skill frequency barcharts and dendrograms were constructed from skills parsed from technical and managerial job postings scraped from Indeed.ca

* one more dendrogram was constructed from results from some questions from Kaggle 2018 Data Science and Machine Learning  survey

### jupyter notebooks

**Indeed_web_scraper_v13.ipynb** -- jupyter notebook with a web scraper used to scrape Data Science related job postings from indeed.ca

* original notebook displays HTMLs of job search pages from which job postings are scraped

* these HTML sections do not render right on GitHub

* downloaded version of the jupyter notebook run locally would have the correct display

**final_jupyter_notebook_verified.ipynb** -- this notebook contains the **detailed description of the workflow** and discussion of results

**skills_heirarchical_clustering.ipynb** -- this notebook presents the construction of dendrograms from scraped data and Kaggle survey results
