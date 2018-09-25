# CompanyCulture
Text Analytics project
Introduction
About 120000 rows of job descriptions were obtained from Glassdoor website. After cleaning and normalizing the text data, we extracted features for each industry and calculated the similarities between each industry by cosine similarity score. We also generated trigrams that are TFIDF weighted.   

1.	Crawling process (when, method, information….)
a.	The period of crawling is from June to July in 2017, (job description is also around similar time, April 2016 earliest time, mostly May, June, July 2017)
b.	Used the module of urllib2 in Python and regular expression to design the crawling program.
c.	The job information in every row includes id, url, title, industry, company name, company score, review number, job type, city, state, posted date and job description.


2.	Data statistics (# of companies, # of job descriptions, average length……., max, min)
a.	Data includes 446 companies from S&P 500.
b.	Crawled 118,677 rows data.
